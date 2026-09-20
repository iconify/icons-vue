<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cbnwcbsoy.css';
import '../../css/h/hhd67iwpx.css';
import '../../css/b/bbrv0_ogo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cbnwcbsoy"/><path class="hhd67iwpx"/><path clip-rule="evenodd" class="bbrv0_ogo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:creative-commons-outline" /></template>
