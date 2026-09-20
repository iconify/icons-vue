<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llhl38_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llhl38_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:clinic-medical" /></template>
