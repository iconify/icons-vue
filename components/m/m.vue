<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcsclub-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kcsclub-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:m" /></template>
