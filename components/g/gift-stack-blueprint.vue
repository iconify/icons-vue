<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vhtshccqs.css';
import '../../css/b/b04599g3z.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/j/ju1mt7bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vhtshccqs wm-deco"/><path class="b04599g3z wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="ju1mt7bfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-stack-blueprint" /></template>
