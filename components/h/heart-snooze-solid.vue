<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhd7pyo3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhd7pyo3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-snooze-solid" /></template>
