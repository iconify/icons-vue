<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydhos9v1w.css';
import '../../css/p/p7zf9gbeq.css';
import '../../css/p/pmv6vn68x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydhos9v1w"/><path class="p7zf9gbeq"/><path class="pmv6vn68x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-vpc-endpoints" /></template>
