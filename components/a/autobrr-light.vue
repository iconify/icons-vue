<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhdef1ytm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhdef1ytm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:autobrr-light" /></template>
