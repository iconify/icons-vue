<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjceg_buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fjceg_buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:kangaroo" /></template>
