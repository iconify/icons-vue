<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcuou08cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuou08cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-lock-outline" /></template>
