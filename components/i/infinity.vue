<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysfpi3b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysfpi3b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:infinity" /></template>
