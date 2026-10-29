<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6kasu72k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p6kasu72k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gemini-wordmark" /></template>
