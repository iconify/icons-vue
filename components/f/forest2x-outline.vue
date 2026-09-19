<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8h4xabsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l8h4xabsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:forest2x-outline" /></template>
