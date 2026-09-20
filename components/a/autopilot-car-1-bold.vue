<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/synvtgbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="synvtgbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:autopilot-car-1-bold" /></template>
