<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-huc-bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-huc-bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:drag-horizontal" /></template>
