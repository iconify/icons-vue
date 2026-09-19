<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh7vsxbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xh7vsxbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:insurance-card" /></template>
