<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrvj_fbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrvj_fbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:egg-easter" /></template>
