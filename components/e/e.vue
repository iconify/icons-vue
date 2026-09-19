<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm6lhw1sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dm6lhw1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:e" /></template>
