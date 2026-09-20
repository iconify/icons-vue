<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i04bx5bgx.css';
import '../../css/w/w88gn2gzc.css';
import '../../css/h/h3388l28h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i04bx5bgx"/><path clip-rule="evenodd" class="w88gn2gzc"/><path class="h3388l28h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-text-filled" /></template>
