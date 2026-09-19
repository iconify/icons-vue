<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csvco9ssf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="csvco9ssf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:leg" /></template>
