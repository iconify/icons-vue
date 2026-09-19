<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps0ot-_-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ps0ot-_-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:drop-of-blood" /></template>
