<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg6pjbb_x.css';
import '../../css/l/l70ob6bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pg6pjbb_x"/><path class="l70ob6bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-sync" /></template>
