<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryxdwcc3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ryxdwcc3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-flow-usage" /></template>
