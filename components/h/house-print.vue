<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eyamk_boj.css';
import '../../css/h/hq22nxb0x.css';
import '../../css/h/hxccg9byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="eyamk_boj"/><path clip-rule="evenodd" class="hq22nxb0x"/><path clip-rule="evenodd" class="hxccg9byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:house-print" /></template>
