<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t059a5r9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t059a5r9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:airplane" /></template>
