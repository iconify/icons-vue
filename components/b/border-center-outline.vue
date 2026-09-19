<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j07ug2b2j.css';
import '../../css/b/be78hac3b.css';
import '../../css/q/q_8ldsbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j07ug2b2j"/><path class="be78hac3b"/><path clip-rule="evenodd" class="q_8ldsbpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-center-outline" /></template>
