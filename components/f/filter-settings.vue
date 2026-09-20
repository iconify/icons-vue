<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny5pi-arz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny5pi-arz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:filter-settings" /></template>
