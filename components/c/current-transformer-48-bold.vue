<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndt99pbau.css';
import '../../css/x/x908mum4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ndt99pbau"/><path class="x908mum4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-transformer-48-bold" /></template>
