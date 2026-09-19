<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7mb3_b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v7mb3_b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heartbeat2x-outline" /></template>
