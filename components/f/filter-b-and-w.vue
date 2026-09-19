<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv91aob2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="lv91aob2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:filter-b-and-w" /></template>
