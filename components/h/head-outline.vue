<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hszka1bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hszka1bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:head-outline" /></template>
