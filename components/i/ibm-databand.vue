<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_efktyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="io_efktyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-databand" /></template>
