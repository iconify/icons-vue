<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n650ikbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n650ikbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:influxdb" /></template>
