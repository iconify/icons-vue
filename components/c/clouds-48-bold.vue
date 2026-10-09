<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzpt0u8pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzpt0u8pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clouds-48-bold" /></template>
