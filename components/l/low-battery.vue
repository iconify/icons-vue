<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gase_7b4q.css';
import '../../css/h/hvi-ie_cu.css';
import '../../css/f/f3f__iguo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gase_7b4q"/><path class="hvi-ie_cu"/><path class="f3f__iguo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:low-battery" /></template>
