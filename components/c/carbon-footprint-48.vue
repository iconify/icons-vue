<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1mc6lwbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1mc6lwbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-footprint-48" /></template>
