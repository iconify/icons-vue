<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydif_wb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ydif_wb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:circle" /></template>
