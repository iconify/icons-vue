<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob-pomunx.css';
import '../../css/v/vq2he1abb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ob-pomunx"/><path class="vq2he1abb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-turbine-48" /></template>
