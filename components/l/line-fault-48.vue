<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_g2f6aqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_g2f6aqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:line-fault-48" /></template>
