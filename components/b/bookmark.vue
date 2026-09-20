<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji2194_ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ji2194_ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:bookmark" /></template>
