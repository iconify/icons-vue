<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9mrh9bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d9mrh9bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-data-security2x-outline" /></template>
