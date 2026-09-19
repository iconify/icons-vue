<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tni516bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tni516bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:large-blue-diamond" /></template>
