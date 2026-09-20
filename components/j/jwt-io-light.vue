<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_vjcckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yr_vjcckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jwt-io-light" /></template>
