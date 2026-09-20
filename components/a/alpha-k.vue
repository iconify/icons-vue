<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0c8ymouc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i0c8ymouc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-k" /></template>
