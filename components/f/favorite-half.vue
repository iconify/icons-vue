<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa1m9d30z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pa1m9d30z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:favorite-half" /></template>
