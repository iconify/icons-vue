<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhp9hjbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uhp9hjbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:doctor" /></template>
