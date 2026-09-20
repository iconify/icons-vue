<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e-uxb6qtx.css';
import '../../css/k/kt_wmkbmo.css';
import '../../css/z/z_v77-bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e-uxb6qtx"/><path class="kt_wmkbmo"/><path class="z_v77-bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-search-bold-duotone" /></template>
