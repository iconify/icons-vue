<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zjnu1hnoa.css';
import '../../css/r/rs61gez4m.css';
import '../../css/s/sf6nefbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="zjnu1hnoa"/><path class="rs61gez4m"/><path class="sf6nefbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:foot-medium" /></template>
