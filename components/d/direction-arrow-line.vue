<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvgx_ibgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvgx_ibgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-arrow-line" /></template>
