<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0a4mhdhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="i0a4mhdhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:book" /></template>
