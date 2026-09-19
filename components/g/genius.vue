<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4-7j5d3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p4-7j5d3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:genius" /></template>
