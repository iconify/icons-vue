<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d8g36nb4x.css';
import '../../css/h/hawj73bow.css';
import '../../css/y/y4sbhjvpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d8g36nb4x"/><path class="hawj73bow"/><path clip-rule="evenodd" class="y4sbhjvpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bullseye" /></template>
