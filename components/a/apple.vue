<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-6326bns.css';
import '../../css/h/h2clnuigs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s-6326bns"/><path class="h2clnuigs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:apple" /></template>
