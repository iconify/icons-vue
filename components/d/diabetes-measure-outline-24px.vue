<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jhegjbgei.css';
import '../../css/c/cm2goxb8k.css';
import '../../css/r/rkhkfhe6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jhegjbgei"/><path clip-rule="evenodd" class="cm2goxb8k"/><path clip-rule="evenodd" class="rkhkfhe6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:diabetes-measure-outline-24px" /></template>
