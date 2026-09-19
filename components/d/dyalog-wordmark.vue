<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8ildbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tj8ildbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:dyalog-wordmark" /></template>
