<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r75-yf7zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r75-yf7zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:burrito" /></template>
