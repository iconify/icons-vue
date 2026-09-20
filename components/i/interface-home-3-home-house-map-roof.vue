<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwfth1zvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bwfth1zvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-home-3-home-house-map-roof" /></template>
