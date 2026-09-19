<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlb99pbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="rlb99pbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:gps-off" /></template>
