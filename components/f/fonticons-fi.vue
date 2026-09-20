<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzhnfb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pxzhnfb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fonticons-fi" /></template>
