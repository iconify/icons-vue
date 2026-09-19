<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5lrvcctm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="d5lrvcctm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bluetooth-search" /></template>
