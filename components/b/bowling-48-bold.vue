<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thsmnl_1a.css';
import '../../css/h/hspx3ob0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thsmnl_1a"/><path class="hspx3ob0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bowling-48-bold" /></template>
