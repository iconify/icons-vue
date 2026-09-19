<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3w5jobuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3w5jobuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:leftwards-hand" /></template>
