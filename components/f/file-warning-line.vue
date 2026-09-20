<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_cbpvx_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_cbpvx_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-warning-line" /></template>
