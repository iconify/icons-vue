<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1-w-prqa.css';
import '../../css/g/g7er_z6_h.css';
import '../../css/y/ysdvwkbgj.css';
import '../../css/d/drpzlxxvu.css';
import '../../css/f/flsifcbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e1-w-prqa"/><path class="g7er_z6_h"/><path class="ysdvwkbgj"/><path class="drpzlxxvu"/><path class="flsifcbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:clarity-wordmark" /></template>
