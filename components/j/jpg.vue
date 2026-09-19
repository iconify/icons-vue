<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw32gyb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yw32gyb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:jpg" /></template>
