<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_2ozb4w.css';
import '../../css/f/famexubdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zp_2ozb4w"/><path class="famexubdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:graph-trend" /></template>
