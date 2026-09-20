<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flx-ib50r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="flx-ib50r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:heat-map-chart-filled" /></template>
