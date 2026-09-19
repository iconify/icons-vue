<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcuqi2bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hcuqi2bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:book" /></template>
