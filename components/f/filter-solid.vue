<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dout1oble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dout1oble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:filter-solid" /></template>
