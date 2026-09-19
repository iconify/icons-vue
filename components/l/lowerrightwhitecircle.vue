<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etftr2brq.css';
import '../../css/i/i4pcs4-lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="etftr2brq"/><circle class="i4pcs4-lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lowerrightwhitecircle" /></template>
