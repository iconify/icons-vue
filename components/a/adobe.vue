<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp9g6ccaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp9g6ccaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:adobe" /></template>
