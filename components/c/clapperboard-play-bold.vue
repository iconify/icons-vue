<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q6oxflbgu.css';
import '../../css/x/xg0kfbcnh.css';
import '../../css/e/eaotdibie.css';
import '../../css/f/f4d5x_t8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q6oxflbgu"/><path class="xg0kfbcnh"/><path clip-rule="evenodd" class="eaotdibie"/><path class="f4d5x_t8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-play-bold" /></template>
