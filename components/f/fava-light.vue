<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz4_n_nrk.css';
import '../../css/i/ipw0oib4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jz4_n_nrk"/><path class="ipw0oib4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fava-light" /></template>
