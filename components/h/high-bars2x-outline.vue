<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aitkfzbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aitkfzbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:high-bars2x-outline" /></template>
