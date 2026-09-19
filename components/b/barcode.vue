<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc7p41gcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dc7p41gcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:barcode" /></template>
