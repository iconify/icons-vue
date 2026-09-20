<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i5r5wp2qu.css';
import '../../css/s/s-matgtmc.css';
import '../../css/x/x4pfyzk4p.css';
import '../../css/w/w_8fmvbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i5r5wp2qu"/><path class="s-matgtmc"/><path class="x4pfyzk4p"/><path clip-rule="evenodd" class="w_8fmvbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-kanban-outline" /></template>
