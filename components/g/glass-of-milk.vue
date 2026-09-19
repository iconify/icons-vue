<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz6m-e_na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fz6m-e_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:glass-of-milk" /></template>
