<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzpozeuvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qzpozeuvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-down-2" /></template>
