<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwawrhueb.css';
import '../../css/d/dq6d_3byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwawrhueb"/><path class="dq6d_3byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-kubernetes-service" /></template>
