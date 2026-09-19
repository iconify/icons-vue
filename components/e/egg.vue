<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsz92fboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jsz92fboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:egg" /></template>
