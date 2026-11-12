<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mo5s6gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8mo5s6gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeresend-dark" /></template>
