<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqx8zr61m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gqx8zr61m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:factory-worker-outline" /></template>
