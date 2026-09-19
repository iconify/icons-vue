<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_upz09w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":408};
const content = `<path class="kc_upz09w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:cloud-off" /></template>
