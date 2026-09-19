<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2e6ehonk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p2e6ehonk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hindu-temple" /></template>
