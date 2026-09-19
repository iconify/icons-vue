<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlcn6fb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mlcn6fb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-diaphragm" /></template>
