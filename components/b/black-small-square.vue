<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aicxeqb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aicxeqb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-small-square" /></template>
