<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gozsv_iaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gozsv_iaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cryengine" /></template>
