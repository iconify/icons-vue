<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdccm0dcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cdccm0dcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:left-right" /></template>
