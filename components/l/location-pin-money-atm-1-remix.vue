<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpgql3bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpgql3bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-pin-money-atm-1-remix" /></template>
