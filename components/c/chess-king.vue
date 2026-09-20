<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogygfci6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ogygfci6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chess-king" /></template>
