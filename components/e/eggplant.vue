<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kit9s8biw.css';
import '../../css/l/lqgc3327d.css';
import '../../css/r/rtlsz678t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="kit9s8biw"/><path class="lqgc3327d"/><path class="rtlsz678t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:eggplant" /></template>
