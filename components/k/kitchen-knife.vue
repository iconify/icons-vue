<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0tfrccvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j0tfrccvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:kitchen-knife" /></template>
