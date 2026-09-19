<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8e6r52as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y8e6r52as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:denojs-wordmark" /></template>
