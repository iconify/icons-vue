<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppqdlmdge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ppqdlmdge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:icd-10" /></template>
