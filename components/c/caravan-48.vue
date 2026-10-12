<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2gdnrblg.css';
import '../../css/l/l8kp85irh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2gdnrblg"/><path class="l8kp85irh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caravan-48" /></template>
