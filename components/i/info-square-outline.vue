<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ik6x-m28o.css';
import '../../css/a/aw-y6obss.css';
import '../../css/u/un073yd9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ik6x-m28o"/><path class="aw-y6obss"/><path clip-rule="evenodd" class="un073yd9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:info-square-outline" /></template>
