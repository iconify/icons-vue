<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9pftxwov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z9pftxwov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hollow-red-circle" /></template>
