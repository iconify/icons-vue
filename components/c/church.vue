<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4u_y1bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4u_y1bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:church" /></template>
