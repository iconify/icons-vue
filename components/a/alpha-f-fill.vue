<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbxlq0bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bbxlq0bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-f-fill" /></template>
