<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x9a1124li.css';
import '../../css/s/s8batg03y.css';
import '../../css/y/yj_5s8bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9a1124li"/><path class="s8batg03y"/><path clip-rule="evenodd" class="yj_5s8bsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-outline" /></template>
