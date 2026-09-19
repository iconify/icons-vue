<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw006larm.css';
import '../../css/f/fiyc44jpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hw006larm"/><path class="fiyc44jpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:junie-wordmark" /></template>
