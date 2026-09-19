<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6u59sxkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s6u59sxkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-shift-down" /></template>
