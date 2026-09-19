<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0yaybfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="un0yaybfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:double-exclamation-mark" /></template>
