<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_29t6_8t.css';
import '../../css/r/rys3lkbnk.css';
import '../../css/s/s5pzo9x7j.css';
import '../../css/m/m90j_eaof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l_29t6_8t"/><path class="rys3lkbnk"/><path clip-rule="evenodd" class="s5pzo9x7j"/><path class="m90j_eaof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bell-print" /></template>
