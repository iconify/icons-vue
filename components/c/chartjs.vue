<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftpedcbgb.css';
import '../../css/a/ai4ebubxr.css';
import '../../css/i/i3dab3_cs.css';
import '../../css/w/wfceq4bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ftpedcbgb"/><path class="ai4ebubxr"/><path class="i3dab3_cs"/><path class="wfceq4bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:chartjs" /></template>
