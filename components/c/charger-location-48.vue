<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-at6e2cq.css';
import '../../css/z/zf-4rt-bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d-at6e2cq"/><path class="zf-4rt-bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-location-48" /></template>
