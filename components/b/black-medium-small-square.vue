<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr2d8z97p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yr2d8z97p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:black-medium-small-square" /></template>
