<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb8s_pcfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sb8s_pcfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hook0-light" /></template>
