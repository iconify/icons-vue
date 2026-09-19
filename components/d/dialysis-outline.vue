<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwza8kbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iwza8kbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:dialysis-outline" /></template>
