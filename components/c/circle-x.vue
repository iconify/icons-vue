<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa34macfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wa34macfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:circle-x" /></template>
