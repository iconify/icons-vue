<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdzognbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wdzognbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:broccoli" /></template>
