<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ios_9nm3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ios_9nm3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:lotus" /></template>
