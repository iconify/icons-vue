<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6qxaebkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6qxaebkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:computer-mouse" /></template>
