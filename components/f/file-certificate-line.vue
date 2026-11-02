<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hruluy_dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hruluy_dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-certificate-line" /></template>
