<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouhuvdbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouhuvdbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:call-me-hand" /></template>
