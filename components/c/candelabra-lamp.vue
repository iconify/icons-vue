<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iso_4ebmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iso_4ebmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:candelabra-lamp" /></template>
