<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfy99w0bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="nfy99w0bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:crop-free" /></template>
