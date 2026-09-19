<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izmr92e0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="izmr92e0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:entry-view" /></template>
