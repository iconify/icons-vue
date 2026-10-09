<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uayzpq5gn.css';
import '../../css/h/hokpvi8xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uayzpq5gn"/><path class="hokpvi8xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jersey-48-bold" /></template>
