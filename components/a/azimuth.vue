<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpna9sbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tpna9sbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:azimuth" /></template>
