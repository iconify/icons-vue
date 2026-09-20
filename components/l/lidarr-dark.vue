<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhghu-bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhghu-bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lidarr-dark" /></template>
