<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osd8-xbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="osd8-xbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera-monochrome-photos" /></template>
