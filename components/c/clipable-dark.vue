<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbgw_bblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbgw_bblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:clipable-dark" /></template>
