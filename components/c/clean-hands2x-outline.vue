<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oz_q5um7a.css';
import '../../css/g/ge5wqcccf.css';
import '../../css/q/qs--2tbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oz_q5um7a"/><path class="ge5wqcccf"/><path clip-rule="evenodd" class="qs--2tbzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:clean-hands2x-outline" /></template>
