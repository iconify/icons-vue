<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga3091btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ga3091btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-hail-48" /></template>
