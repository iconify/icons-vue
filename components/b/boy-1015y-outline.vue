<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drv7s9bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="drv7s9bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:boy-1015y-outline" /></template>
