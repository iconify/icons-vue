<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d05jkvbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d05jkvbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:green-book" /></template>
