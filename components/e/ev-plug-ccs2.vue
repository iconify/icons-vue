<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhrmt3b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrmt3b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ev-plug-ccs2" /></template>
