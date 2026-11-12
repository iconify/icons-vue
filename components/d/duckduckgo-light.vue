<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypknmkbto.css';
import '../../css/r/ra8213bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypknmkbto"/><path class="ra8213bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckduckgo-light" /></template>
