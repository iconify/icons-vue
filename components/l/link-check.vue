<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd9tabcpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd9tabcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:link-check" /></template>
