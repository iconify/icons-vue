<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-2q8bc0s.css';
import '../../css/s/s4czx2bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-2q8bc0s"/><path class="s4czx2bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hawser-light" /></template>
