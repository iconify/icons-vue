<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s33ndsrce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s33ndsrce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alarmpi-light" /></template>
