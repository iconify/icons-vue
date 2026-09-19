<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7nqu2bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i7nqu2bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:boomerang" /></template>
