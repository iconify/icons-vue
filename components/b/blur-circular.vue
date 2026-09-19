<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snst5v0nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="snst5v0nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:blur-circular" /></template>
