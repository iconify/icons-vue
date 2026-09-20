<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avrpgvsbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avrpgvsbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-chart-fill" /></template>
