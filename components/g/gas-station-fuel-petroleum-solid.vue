<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfdgs3bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfdgs3bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gas-station-fuel-petroleum-solid" /></template>
