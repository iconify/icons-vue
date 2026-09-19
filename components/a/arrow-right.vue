<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mztns1gty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mztns1gty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-right" /></template>
