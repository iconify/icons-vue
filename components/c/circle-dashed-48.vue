<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzje2pbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xzje2pbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circle-dashed-48" /></template>
