<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m3duksq9k.css';
import '../../css/p/pmv50n_jk.css';
import '../../css/f/fbnjgqhbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m3duksq9k"/><path class="pmv50n_jk"/><path class="fbnjgqhbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:download" /></template>
