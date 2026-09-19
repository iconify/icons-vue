<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sqhe39_lk.css';
import '../../css/g/g3hxb2bcp.css';
import '../../css/f/fpfjyjotr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sqhe39_lk"/><path class="g3hxb2bcp"/><path class="fpfjyjotr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:admission-tickets" /></template>
