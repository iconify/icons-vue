<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgiy9tb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgiy9tb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bright-button" /></template>
