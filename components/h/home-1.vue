<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz2p7bcuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vz2p7bcuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:home-1" /></template>
