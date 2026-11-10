<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnva4_vbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hnva4_vbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:groq-wordmark" /></template>
