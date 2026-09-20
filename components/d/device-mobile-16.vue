<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox2gpx_xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ox2gpx_xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-mobile-16" /></template>
