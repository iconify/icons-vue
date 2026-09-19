<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3v0e9b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x3v0e9b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:candy" /></template>
