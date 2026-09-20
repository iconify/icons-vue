<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kbm5ejlhj.css';
import '../../css/p/p598gbcpi.css';
import '../../css/h/h38drbc1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kbm5ejlhj"/><path class="p598gbcpi"/><path class="h38drbc1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:heading" /></template>
