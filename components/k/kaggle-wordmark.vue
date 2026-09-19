<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjesxm3-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mjesxm3-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kaggle-wordmark" /></template>
