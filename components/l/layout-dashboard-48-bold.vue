<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ri8jbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7ri8jbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-dashboard-48-bold" /></template>
