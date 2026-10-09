<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfiv_5beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfiv_5beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iceberg-48" /></template>
