<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi2p_hbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi2p_hbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:grid-off" /></template>
