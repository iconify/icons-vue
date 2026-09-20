<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrb4cv34j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xrb4cv34j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:camera-slr" /></template>
