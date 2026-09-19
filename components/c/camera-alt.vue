<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znb0yccba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="znb0yccba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-alt" /></template>
