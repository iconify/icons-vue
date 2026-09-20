<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5_g_lbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5_g_lbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:checkcle-light" /></template>
