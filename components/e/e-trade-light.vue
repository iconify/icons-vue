<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp2db-b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mp2db-b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:e-trade-light" /></template>
