<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfe_d_2bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfe_d_2bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-station-in-use-outline" /></template>
