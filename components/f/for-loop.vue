<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o52mxibjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o52mxibjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:for-loop" /></template>
