<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuefa0btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="fuefa0btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-flag" /></template>
