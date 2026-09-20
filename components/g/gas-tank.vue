<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtl23bc2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtl23bc2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-tank" /></template>
