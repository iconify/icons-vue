<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubsgd0b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubsgd0b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hourglass-done" /></template>
