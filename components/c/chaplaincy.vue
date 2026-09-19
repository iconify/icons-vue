<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke1y0kp2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ke1y0kp2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chaplaincy" /></template>
