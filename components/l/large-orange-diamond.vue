<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4df0dbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h4df0dbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:large-orange-diamond" /></template>
