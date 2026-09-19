<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu6db3bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eu6db3bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bucket" /></template>
