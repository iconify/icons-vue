<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyar77b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pyar77b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:double-curly-loop" /></template>
