<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk8ignbif.css';
import '../../css/f/f4xt2vwuy.css';
import '../../css/w/w6jv0yfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dk8ignbif"/><path class="f4xt2vwuy"/><path class="w6jv0yfwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dial-indicator-48-bold" /></template>
