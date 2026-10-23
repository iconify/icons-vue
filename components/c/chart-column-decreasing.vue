<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcm_16b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcm_16b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-column-decreasing" /></template>
