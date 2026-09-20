<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-h3xgbno.css';
import '../../css/k/k-2dhebbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-h3xgbno"/><path class="k-2dhebbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gauge-dashboard-bold" /></template>
