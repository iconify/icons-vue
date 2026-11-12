<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_85zbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1_85zbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:influxdb-light" /></template>
