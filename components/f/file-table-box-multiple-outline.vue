<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tev1h3bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tev1h3bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-table-box-multiple-outline" /></template>
