<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_y96qtkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g_y96qtkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:credit-card2x-outline" /></template>
