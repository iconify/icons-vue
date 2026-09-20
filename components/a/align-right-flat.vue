<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzlt_3t1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wzlt_3t1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:align-right-flat" /></template>
