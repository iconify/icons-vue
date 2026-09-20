<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl_6u4_hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl_6u4_hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-home-light" /></template>
