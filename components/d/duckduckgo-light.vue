<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypknmkbto.css';
import '../../css/g/g1k_hynjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypknmkbto"/><path class="g1k_hynjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duckduckgo-light" /></template>
