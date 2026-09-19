<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjhd4upqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hjhd4upqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:child" /></template>
