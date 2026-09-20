<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc6ugedaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc6ugedaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:joomla-dark" /></template>
