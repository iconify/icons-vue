<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-cmf8bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h-cmf8bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:autoimmune-disease-outline" /></template>
