<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmx1_t3-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmx1_t3-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bolt-48" /></template>
