<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsjz-2bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="dsjz-2bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bluetooth-off" /></template>
