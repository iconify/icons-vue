<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiyct_b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wiyct_b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:animation-digital-network-light" /></template>
