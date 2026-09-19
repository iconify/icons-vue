<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcp4ccdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qfcp4ccdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:8-outline" /></template>
