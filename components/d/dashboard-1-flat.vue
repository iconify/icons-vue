<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca2293b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ca2293b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:dashboard-1-flat" /></template>
