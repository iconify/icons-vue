<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5fq7hrmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d5fq7hrmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:carrot" /></template>
