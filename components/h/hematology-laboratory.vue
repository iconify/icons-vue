<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb_s7xb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bb_s7xb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hematology-laboratory" /></template>
