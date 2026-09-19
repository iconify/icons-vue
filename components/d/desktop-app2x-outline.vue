<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm52ebcgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rm52ebcgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:desktop-app2x-outline" /></template>
