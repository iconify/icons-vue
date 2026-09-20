<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub4bgwhty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub4bgwhty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cnbc-dark" /></template>
