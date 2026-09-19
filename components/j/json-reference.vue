<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_w6esxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oe_w6esxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:json-reference" /></template>
