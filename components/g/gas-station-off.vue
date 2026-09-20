<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te31bcj7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te31bcj7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gas-station-off" /></template>
