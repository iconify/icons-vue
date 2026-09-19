<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugvlctb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ugvlctb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-webmethods-b2b-integration" /></template>
