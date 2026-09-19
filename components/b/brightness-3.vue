<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvd_txbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":432};
const content = `<path class="vvd_txbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-3" /></template>
