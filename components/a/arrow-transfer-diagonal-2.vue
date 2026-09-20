<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx-wx-b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cx-wx-b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-transfer-diagonal-2" /></template>
