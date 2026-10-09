<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd8a8ccdm.css';
import '../../css/x/x2-lnebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fd8a8ccdm"/><path class="x2-lnebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammer-48-bold" /></template>
