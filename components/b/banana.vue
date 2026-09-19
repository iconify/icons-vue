<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w92xktbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w92xktbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:banana" /></template>
