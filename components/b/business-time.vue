<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el1y1abrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="el1y1abrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:business-time" /></template>
