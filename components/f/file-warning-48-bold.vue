<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdos38jip.css';
import '../../css/u/uz1swlb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdos38jip"/><path class="uz1swlb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-warning-48-bold" /></template>
