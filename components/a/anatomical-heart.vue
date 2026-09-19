<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obybe6j6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="obybe6j6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:anatomical-heart" /></template>
