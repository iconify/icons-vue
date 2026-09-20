<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5my2xbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u5my2xbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bentopdf-light" /></template>
