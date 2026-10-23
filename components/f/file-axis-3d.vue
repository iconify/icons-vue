<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7wms___w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7wms___w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-axis-3d" /></template>
