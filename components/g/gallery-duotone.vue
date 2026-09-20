<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i7tbtit9u.css';
import '../../css/i/idc33h8qs.css';
import '../../css/w/wb5s-abgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i7tbtit9u"/><path clip-rule="evenodd" class="idc33h8qs"/><path class="wb5s-abgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gallery-duotone" /></template>
