<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz5s9uirz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wz5s9uirz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:joints-outline" /></template>
