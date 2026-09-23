<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc_9f5b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc_9f5b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aiometadata-light" /></template>
