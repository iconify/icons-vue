<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgm_fab8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgm_fab8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-location" /></template>
