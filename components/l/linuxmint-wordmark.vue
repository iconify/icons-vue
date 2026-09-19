<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-0eilb3d.css';
import '../../css/s/spf_dtebf.css';
import '../../css/v/vrm0gtb4l.css';
import '../../css/g/gi6z60bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q-0eilb3d"/><path class="spf_dtebf"/><path class="vrm0gtb4l"/><path class="gi6z60bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:linuxmint-wordmark" /></template>
