<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u___c24ko.css';
import '../../css/d/de4-70ccf.css';
import '../../css/q/q1egusbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="u___c24ko"/><path clip-rule="evenodd" class="de4-70ccf"/><path class="q1egusbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:color-picker-off" /></template>
