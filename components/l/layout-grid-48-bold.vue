<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_-qooub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tb_-qooub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layout-grid-48-bold" /></template>
