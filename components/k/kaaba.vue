<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5_99bc0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5_99bc0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:kaaba" /></template>
