<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ounxby0eh.css';
import '../../css/r/rs61gez4m.css';
import '../../css/a/axicx3eyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ounxby0eh"/><path class="rs61gez4m"/><path class="axicx3eyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:foot-light" /></template>
