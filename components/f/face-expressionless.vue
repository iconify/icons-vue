<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxcdi_e3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxcdi_e3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:face-expressionless" /></template>
