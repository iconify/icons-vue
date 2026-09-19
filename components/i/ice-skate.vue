<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncxchm-0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ncxchm-0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ice-skate" /></template>
