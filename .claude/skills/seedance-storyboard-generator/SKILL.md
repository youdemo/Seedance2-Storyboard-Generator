---
name: seedance-storyboard-generator
description: Professional AI video script and storyboard generator for Seedance 2.0 platform. Use when user asks to: (1) Convert articles/stories into video scripts, (2) Generate Seedance 2.0 storyboard prompts, (3) Plan multi-episode AI video series, (4) Create character/scene/prop generation prompts for image models like Nana Banana Pro. Input can be full novels, articles, or brief story outlines. Output includes complete screenplay with standard script format (△镜头描述+对白+OS/VO+闪回+字幕), episode breakdown, asset generation prompts, and Seedance 2.0 formatted storyboard scripts.
---

# Seedance Storyboard Generator

Expert AI script and storyboard generation system for creating professional AI video series on Seedance 2.0 platform.

## Workflow

Follow this sequential process to convert source material into production-ready video scripts:

### 1. Analyze Input

**Determine input type:**
- **Full text**: Complete novel/article requiring adaptation and episode segmentation
- **Outline**: Brief story concept requiring full script development

**Extract core elements:**
- Protagonist(s) and key characters
- Central conflict and narrative arc
- Setting/world-building elements
- Key plot points and emotional beats
- Core hook/selling point

Ask clarifying questions if input is ambiguous or incomplete.

### 2. Confirm Production Parameters

**Essential questions to ask:**

1. **Visual Style**: What visual style? (写实/动画/水墨/科幻/复古/电影感/其他)
2. **Duration**: Total runtime? (Standard: 5 episodes × 15s each ≈ 75 seconds for short series; 20 episodes × 15s ≈ 5 minutes for full series)
3. **Target Platform**: Aspect ratio? (16:9横屏 / 9:16竖屏 / 2.35:1电影宽屏)
4. **Tone**: Overall emotional tone? (史诗/温馨/悬疑/欢快/忧伤等)
5. **Core Hook**: What's the one-sentence selling point? (绝境反杀/复仇爽剧/治愈温馨/悬疑惊悚等)

Document these parameters for consistent application throughout.

### 3. Generate Complete Screenplay Structure

**IMPORTANT: Output must follow the exact format shown below, matching "好剧本.md" quality standards.**

#### 3.1 Output Format - Part 1: Story Analysis

```
# [Title] - 剧本

一、核心梗
[Two-word or short phrase core hook, e.g., 绝境反杀、经典武侠、复仇爽剧]

二、故事梗概
故事背景：[Time period, location, initial situation]
开场冲突：[What breaks the status quo, inciting incident]
主角画像：[Who is the protagonist, their core trait, current state]
主线事件：[Key plot progression → climax → resolution]
结局：[Final outcome, character transformation]

三、一句话卖点
[Punchy marketing hook with emotion, e.g., 忍无可忍，无须再忍！风雪夜，豹子头林冲长枪出鞘，血溅山神庙！]

四、人物小传
[For EACH main character include:]

**角色名**
视觉形象：[Age, appearance details, clothing, key visual markers]
身份背景：[Social role, background, relationship to protagonist]
核心标签：[2-4 character traits, e.g., 隐忍不发、悲情英雄、杀神降临]
性格特点：[Detailed personality description, arc transformation]
金句：[Memorable line that captures their essence]

五、剧本大纲
前期（起）：[Setup - establish world, protagonist, status quo]
中期（承/转）：[Conflict development, complications, turning point]
后期（高潮）：[Climax, confrontation, emotional peak]
尾声（收尾）：[Resolution, aftermath, thematic closure]

六、剧本正文
```

#### 3.2 Output Format - Part 2: Script Body (Each Episode)

**CRITICAL: Each episode must use the EXACT format below:**

```
第X集
X-X [日/夜] [内/外] [场景名称]
道具：[List key props]
出场人物：[List characters in scene]

△ 【空镜/开场镜头】[Detailed shot description with camera movement, composition, lighting, atmosphere]
△ [Shot 2 description with specific camera movement: 推/拉/摇/移/跟/环绕/升降/特写/远景]
△ [Shot 3 description - continue for each beat]
角色名（os）：[Interior monologue/voiceover]
△ [Reaction shot description]
角色名（对白/动作描述）：[Spoken dialogue]
△ [Action/sequence description]
【字幕：xxx】[When on-screen text is needed]
△ [Scene continuation]
△ 【闪回】[Flashback scene description]
[Flashback content with △ shots]
【闪回结束】
△ [Return to present, reaction]
角色名（vo）：[Voiceover from off-screen character]
△ [Climactic action sequence]
△ 【空镜】[Closing atmospheric shot]
【字幕：xxx】
```

**Script Format Rules:**

1. **Every shot starts with `△ `** (triangle + space)
2. **Camera language must be specific:**
   - 景别：远景/全景/中景/近景/特写/大特写
   - 运镜：推镜头/拉镜头/摇镜头/移镜头/跟镜头/环绕镜头/升降镜头/希区柯克变焦/一镜到底/手持晃动
   - 组合：`中景推近`、`特写环绕`、`远景俯拍`、`快速推近`、`缓慢拉远`

3. **Dialogue notation:**
   - `角色名（os）` - 画外音/内心独白 (off-screen sound/interior monologue)
   - `角色名（vo）` - 画外音，人物不在画面中 (voiceover)
   - `角色名（惊/怒/喜）` - 带情绪的对白
   - `角色名` - 普通对白

4. **Special elements:**
   - `【空镜】` - Establishing/atmospheric shot without characters
   - `【闪回】` / `【闪回结束】` - Flashback sequence
   - `【字幕：xxx】` - On-screen text/titles

5. **Action description format:**
   - Use `→` for action sequences: `林冲一枪刺穿差拨胸膛 → 鲜血喷溅 → 雪地染红`
   - Use emotive language: `杀气冲天`、`眼中怒火燃烧`、`浑身颤抖`

6. **Sensory details:**
   - Visual: 颜色、光影、构图、氛围
   - Auditory: 声音描述融入镜头中
   - Tactile: 寒冷、疼痛、质感

### 4. Create Asset Generation Plan

**Categorize and number all visual assets:**

| Category | Prefix | Example | Description |
|----------|--------|---------|-------------|
| Characters | C01-C99 | C01 林冲·正面全身 | Multiple angles per character |
| Scenes | S01-S99 | S01 沧州草料场·雪景 | Key locations |
| Props | P01-P99 | P01 长枪 | Important objects |

**Asset generation prompt format:**
```
### [编号] — [名称]

[Style prefix], [detailed visual description in English], [technical specs]

**Style Prefix Examples:**
- Chinese ink wash painting style mixed with anime cel-shading
- Cinematic photorealistic style with dramatic lighting
- 3D Pixar-style animation rendering
- Sci-fi cyberpunk aesthetic with neon lighting

**Character differentiation:** Use distinct color schemes and visual markers for each character to ensure recognition in the chosen art style.
```

**Output format:** Organized list with unique IDs, suitable for copy-pasting into image generators.

### 5. Generate Seedance 2.0 Storyboard Scripts

**For each episode, produce:**

**a. Asset Upload List**
```
| 上传位置 | 素材ID | 素材描述 |
| 图片1 | C01 | 林冲正面全身（角色一致性参考） |
| 图片2 | S01 | 草料场场景参考 |
```

**b. Seedance Prompt (Time-axis format)**
```
[英文风格描述]，[时长]，[画幅比例]，[整体氛围]

0-3s: [建立场景] - [镜头运动]，[详细画面描述]，[氛围营造]

3-6s: [主体引入/情节发展] - [镜头运动]，[具体动作]，[情绪表达]

6-9s: [发展/冲突] - [镜头运动]，[关键动作]，[细节特写]

9-12s: [高潮/转折] - [镜头运动]，[情绪爆发]，[视觉冲击]

12-15s: [结尾/落版] - [镜头运动]，[最终画面]，[余韵]

【声音】[配乐风格] + [音效] + [对白/旁白]

【参考】@图片1 [用途说明]，@图片2 [用途说明]，@图片3 [用途说明]...
```

**c. Ending Frame Description**
- Document the final frame content for next episode continuity
- Include: 主体、背景、光线、构图、氛围

**Camera movement keywords:** 推镜头/拉镜头/摇镜头/移镜头/跟镜头/环绕镜头/升降镜头/希区柯克变焦/一镜到底/手持晃动

**For episode chaining (Ep 2+):** Start prompt with `将@视频1延长15s` and upload previous episode as video reference.

## Output Files

Generate these deliverable files:

1. **[Title]_剧本.md** - Complete screenplay with:
   - 核心梗
   - 故事梗概（背景/冲突/主角/主线/结局）
   - 一句话卖点
   - 人物小传（视觉形象/身份/标签/性格/金句）
   - 剧本大纲（起承转合）
   - 剧本正文（△镜头格式 + 对白 + OS/VO + 闪回 + 字幕）

2. **[Title]_素材清单.md** - All character/scene/prop generation prompts

3. **[Title]_E[XX]_分镜.md** - Individual episode storyboard scripts with time-axis format

## Script Writing Guidelines

### Pacing for 15-Second Episodes

| Episode Type | Number of Shots | Pacing |
|--------------|-----------------|--------|
| Dialogue/Emotion | 3-4 shots | 4-5秒 per shot |
| Action/Combat | 5-7 shots | 2-3秒 per shot |
| Montage/Sequence | 6-8 shots | 2秒 per shot |

### Emotional Progression

Each 15-second episode should have:
- **Opening (0-3s)**: Establish emotion/atmosphere
- **Build (3-9s)**: Rising tension or development
- **Climax (9-12s)**: Emotional peak or key revelation
- **Release (12-15s)**: Resolution or cliffhanger

### Visual Consistency

- Maintain consistent art style across all asset prompts
- Use unique visual markers for each character (color, silhouette, accessories)
- Reference lighting and time of day in scene descriptions

## Quality Assurance

**Before finalizing:**
- ✅ Verify all asset references (@图片X) have corresponding IDs in asset list
- ✅ Check episode-to-episode continuity (ending frame → opening frame)
- ✅ Ensure time-axis coverage spans complete 15 seconds
- ✅ Validate that camera movements are feasible and logically sequenced
- ✅ Confirm script uses proper △ format with specific camera language
- ✅ Check that all dialogue is properly marked (os/vo/emotion)
- ✅ Include sensory details (visual, auditory, atmosphere)
- ✅ Verify each episode has emotional arc (opening → build → climax → release)

## Reference Material

For detailed Seedance 2.0 prompt patterns, templates, and best practices, see [references/seedance-manual.md](references/seedance-manual.md).

Key reference sections:
- Templates 1-16 for different video types (叙事/产品/角色/风景/战争/等)
- Camera movement quick reference
- Atmosphere keyword library
- Multimodal reference syntax (@图片X, @视频X, @音频X)

## Common Pitfalls to Avoid

1. **Sensitive words**: Seedance may reject content with certain terms. Avoid common triggers or use alternative phrasing.
2. **Over-complex prompts**: Long prompts (300+ words) may have inconsistent instruction following. Prefer clarity over verbosity.
3. **Missing continuity**: Always document ending frames and verify next episode starts with matching scene.
4. **Inconsistent style**: Apply same visual style prefix to all asset generation prompts.
5. **Vague camera language**: Avoid generic descriptions like "镜头移动" - use specific terms like "推镜头"、"环绕镜头"。
6. **Missing sensory details**: Script should evoke not just visual but also sound, temperature, texture.
7. **Flat emotional arc**: Each episode needs emotional progression, not just plot points.

## Example Comparison

**❌ BAD (Vague outline):**
```
关键情节：
- 林冲听到门外有人说话
- 得知高球要烧死自己的阴谋
- 冲出去报仇
```

**✅ GOOD (Standard script format):**
```
△ 林冲屏住呼吸，悄无声息地起身，贴在门缝边偷听。
△ 门外的声音透过风雪传来，清晰可辨。
陆谦（vo）：这把火下去，管教他林冲死无葬身之地！
差拨（vo）：陆大人放心，就算烧不死他，失了草料场也是死罪！
△ 林冲听到"高太尉"三字，浑身一震，眼中原本的隐忍瞬间化为熊熊怒火。
△ 【闪回】高衙内调戏妻子、自己误入白虎堂、刺配沧州的画面如走马灯般闪过。
【闪回结束】
△ 林冲死死抓着枪杆，指节因用力而泛白，牙齿咬得咯咯作响。
林冲（os）：陆谦！我待你不薄，你却要置我于死地！
△ 门外传来泼油的声音，火光瞬间映红了门缝。
△ 林冲猛地抬头，杀气冲天，原本的颓废一扫而空。
```
