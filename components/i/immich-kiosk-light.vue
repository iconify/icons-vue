<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/img8m6dpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="img8m6dpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-kiosk-light" /></template>
