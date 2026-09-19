<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euzqdr04x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="euzqdr04x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:index-pointing-up" /></template>
