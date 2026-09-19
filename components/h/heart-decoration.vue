<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsx_icc1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xsx_icc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:heart-decoration" /></template>
