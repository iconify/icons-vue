<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik01-rb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ik01-rb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:clamp" /></template>
