<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1ay_wb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h1ay_wb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chevron-down-solid" /></template>
