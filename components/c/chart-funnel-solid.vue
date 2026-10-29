<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eruqiz5jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eruqiz5jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-funnel-solid" /></template>
