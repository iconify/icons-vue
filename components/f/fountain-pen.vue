<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8jyqp8ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8jyqp8ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:fountain-pen" /></template>
