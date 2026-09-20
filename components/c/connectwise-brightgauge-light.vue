<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s53e0bcnh.css';
import '../../css/p/phkuhv_dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s53e0bcnh"/><path class="phkuhv_dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-brightgauge-light" /></template>
