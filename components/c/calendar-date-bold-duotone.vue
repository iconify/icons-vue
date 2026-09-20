<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i26_dr7-d.css';
import '../../css/p/pn9euabkh.css';
import '../../css/k/kt_wmkbmo.css';
import '../../css/z/z_v77-bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i26_dr7-d"/><path clip-rule="evenodd" class="pn9euabkh"/><path class="kt_wmkbmo"/><path class="z_v77-bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-date-bold-duotone" /></template>
