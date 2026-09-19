<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd9s1h7jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yd9s1h7jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-data-sync2x-outline" /></template>
