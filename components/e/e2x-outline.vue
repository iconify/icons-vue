<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbi8b00up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mbi8b00up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:e2x-outline" /></template>
