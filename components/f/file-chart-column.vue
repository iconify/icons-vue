<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7nrm2b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7nrm2b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-chart-column" /></template>
