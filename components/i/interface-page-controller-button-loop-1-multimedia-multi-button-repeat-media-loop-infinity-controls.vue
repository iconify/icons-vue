<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wba2_jwct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wba2_jwct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-page-controller-button-loop-1-multimedia-multi-button-repeat-media-loop-infinity-controls" /></template>
