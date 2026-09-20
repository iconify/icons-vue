<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i408sxblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i408sxblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-minus-outline" /></template>
