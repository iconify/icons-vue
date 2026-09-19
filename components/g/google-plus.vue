<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmxl5mk7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="xmxl5mk7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-plus" /></template>
