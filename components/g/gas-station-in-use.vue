<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xijb7ktck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xijb7ktck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-station-in-use" /></template>
