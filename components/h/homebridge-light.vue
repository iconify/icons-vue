<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_yv0yb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_yv0yb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homebridge-light" /></template>
