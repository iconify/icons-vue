<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny8cpvbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny8cpvbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:goatcounter-dark" /></template>
