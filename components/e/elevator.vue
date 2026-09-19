<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu-w0ybfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu-w0ybfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:elevator" /></template>
