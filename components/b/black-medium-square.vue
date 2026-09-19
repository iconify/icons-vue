<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbn3v1bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbn3v1bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:black-medium-square" /></template>
