<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihy1ahb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ihy1ahb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:collision" /></template>
