<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/futyw_qpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="futyw_qpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-calendar-light" /></template>
