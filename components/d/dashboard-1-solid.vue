<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9cbnmlce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u9cbnmlce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dashboard-1-solid" /></template>
