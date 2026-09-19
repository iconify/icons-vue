<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-1_1ma1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w-1_1ma1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:long-drum" /></template>
