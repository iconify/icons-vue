<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxm6s-w5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxm6s-w5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-cloud-light" /></template>
