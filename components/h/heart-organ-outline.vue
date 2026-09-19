<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh2ht-bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zh2ht-bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heart-organ-outline" /></template>
