<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e_rw3tb2y.css';
import '../../css/f/f5mcp3p6l.css';
import '../../css/m/myds06t7f.css';
import '../../css/k/kqbg0g8jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e_rw3tb2y"/><path class="f5mcp3p6l"/><path class="myds06t7f"/><path class="kqbg0g8jb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:basketball-linear" /></template>
