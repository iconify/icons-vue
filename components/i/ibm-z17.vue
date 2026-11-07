<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-euup4el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h-euup4el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z17" /></template>
