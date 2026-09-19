<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk70cdcpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="wk70cdcpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dot-circle" /></template>
