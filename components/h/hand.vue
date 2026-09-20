<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z20251bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z20251bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:hand" /></template>
