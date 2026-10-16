<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo1xknbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oo1xknbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-dashboard-48" /></template>
