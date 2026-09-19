<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqf_wfdiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pqf_wfdiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:exercise-walk-supported" /></template>
