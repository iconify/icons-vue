<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyqtdp_mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyqtdp_mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gift-off-outline" /></template>
