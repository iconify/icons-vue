<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g825mr9gl.css';
import '../../css/n/nmtpehbcc.css';
import '../../css/x/xth5tgb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g825mr9gl"/><path class="nmtpehbcc"/><path class="xth5tgb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-paste-solid" /></template>
