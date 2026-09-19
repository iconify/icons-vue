<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khgbpnbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="khgbpnbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-data-replication" /></template>
