<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3bdnpo7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d3bdnpo7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:girl" /></template>
