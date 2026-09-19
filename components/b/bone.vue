<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh2_1rb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sh2_1rb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bone" /></template>
