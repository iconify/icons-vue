<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut-71fb_j.css';
import '../../css/n/nlgbk_b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ut-71fb_j"/><path class="nlgbk_b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:k3os-wordmark" /></template>
