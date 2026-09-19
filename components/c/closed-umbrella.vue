<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn0-01bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xn0-01bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:closed-umbrella" /></template>
