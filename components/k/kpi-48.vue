<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxbs21b9m.css';
import '../../css/e/ezub0eyvb.css';
import '../../css/f/fzbp9rx-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxbs21b9m"/><path class="ezub0eyvb"/><path class="fzbp9rx-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kpi-48" /></template>
