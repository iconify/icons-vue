<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrhr15z4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrhr15z4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-report-filled" /></template>
