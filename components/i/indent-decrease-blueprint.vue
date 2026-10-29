<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fci6hf7ny.css';
import '../../css/m/mhdr543mh.css';
import '../../css/e/e18g5nbpy.css';
import '../../css/n/nuq9sybcn.css';
import '../../css/e/e166uhm4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fci6hf7ny wm-deco"/><path class="mhdr543mh wm-deco"/><path class="e18g5nbpy wm-k"/><path class="nuq9sybcn wm-a"/><path class="e166uhm4q wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indent-decrease-blueprint" /></template>
