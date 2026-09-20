<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgw_5gsvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgw_5gsvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-send" /></template>
