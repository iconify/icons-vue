<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7wc_ybpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7wc_ybpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homedock-os-light" /></template>
