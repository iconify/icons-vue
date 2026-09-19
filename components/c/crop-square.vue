<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmfxt0bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="fmfxt0bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-square" /></template>
