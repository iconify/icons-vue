<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-8vxrbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v-8vxrbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-enterprise-db2" /></template>
