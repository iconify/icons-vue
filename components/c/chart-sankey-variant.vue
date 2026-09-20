<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l155kb_ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l155kb_ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-sankey-variant" /></template>
