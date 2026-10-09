<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpcie8_sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bpcie8_sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-48-bold" /></template>
