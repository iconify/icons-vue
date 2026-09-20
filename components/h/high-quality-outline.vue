<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nxkw0pebi.css';
import '../../css/f/f1vp1rstx.css';
import '../../css/b/bbrv0_ogo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nxkw0pebi"/><path class="f1vp1rstx"/><path clip-rule="evenodd" class="bbrv0_ogo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:high-quality-outline" /></template>
