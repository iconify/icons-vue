<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g00wchmdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g00wchmdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cut-of-meat" /></template>
