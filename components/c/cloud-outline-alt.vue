<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldlei_y_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="ldlei_y_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-outline-alt" /></template>
