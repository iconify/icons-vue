<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2bqm2ptp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2bqm2ptp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-recording" /></template>
