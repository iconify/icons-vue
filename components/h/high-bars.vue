<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gve8z2b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gve8z2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:high-bars" /></template>
