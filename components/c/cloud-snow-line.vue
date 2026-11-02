<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1-osbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp1-osbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-snow-line" /></template>
