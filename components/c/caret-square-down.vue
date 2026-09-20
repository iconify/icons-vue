<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/copc66w9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="copc66w9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-square-down" /></template>
