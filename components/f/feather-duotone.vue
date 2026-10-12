<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iyxlttl6b.css';
import '../../css/j/jik13iwkx.css';
import '../../css/w/whtp5ljmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iyxlttl6b"/><path class="jik13iwkx"/><path class="whtp5ljmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:feather-duotone" /></template>
