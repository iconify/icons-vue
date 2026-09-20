<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw_19yq0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xw_19yq0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ingestion" /></template>
