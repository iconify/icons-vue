<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-esobfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pl-esobfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:algolia-wordmark" /></template>
