<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg2cq_bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pg2cq_bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flaresolverr-dark" /></template>
