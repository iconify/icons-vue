<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uvnty7bzi.css';
import '../../css/f/fjuczkess.css';
import '../../css/a/acwtkzbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uvnty7bzi"/><path class="fjuczkess"/><path class="acwtkzbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-bold-duotone" /></template>
