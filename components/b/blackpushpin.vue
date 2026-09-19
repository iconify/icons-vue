<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt0xhaboe.css';
import '../../css/d/d_rfajbtq.css';
import '../../css/y/yalo82bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rt0xhaboe"/><path class="d_rfajbtq"/><path class="yalo82bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackpushpin" /></template>
