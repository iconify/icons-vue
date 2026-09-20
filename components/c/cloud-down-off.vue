<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g7z1gubub.css';
import '../../css/p/p2vd3xbgk.css';
import '../../css/j/j3gpqnbek.css';
import '../../css/m/mmdgk3bof.css';
import '../../css/u/u1i3dbl4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g7z1gubub"/><path clip-rule="evenodd" class="p2vd3xbgk"/><path class="j3gpqnbek"/><path class="mmdgk3bof"/><path class="u1i3dbl4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:cloud-down-off" /></template>
