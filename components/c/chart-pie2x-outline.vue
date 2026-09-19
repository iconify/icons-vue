<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msnimri5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="msnimri5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-pie2x-outline" /></template>
