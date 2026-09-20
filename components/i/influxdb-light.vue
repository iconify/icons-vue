<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rucyk-uej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rucyk-uej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:influxdb-light" /></template>
