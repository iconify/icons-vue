<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiomx44uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iiomx44uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:framework-dark" /></template>
