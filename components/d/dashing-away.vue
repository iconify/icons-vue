<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-vwrczr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vl-vwrczr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:dashing-away" /></template>
