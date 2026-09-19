<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv17vp8ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vv17vp8ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:adhesive-bandage" /></template>
