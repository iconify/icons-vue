<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwh1grb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh1grb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-play-outline" /></template>
