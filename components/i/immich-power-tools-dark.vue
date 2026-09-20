<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz5bqhgic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vz5bqhgic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-power-tools-dark" /></template>
