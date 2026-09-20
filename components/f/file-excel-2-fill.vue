<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp0akibsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp0akibsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-excel-2-fill" /></template>
