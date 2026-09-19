<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0-vmgb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b0-vmgb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospitalized-outline" /></template>
