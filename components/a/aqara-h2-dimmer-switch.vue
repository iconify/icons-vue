<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um8f6_zry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um8f6_zry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h2-dimmer-switch" /></template>
