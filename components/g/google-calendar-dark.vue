<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdjg2gbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fdjg2gbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-calendar-dark" /></template>
