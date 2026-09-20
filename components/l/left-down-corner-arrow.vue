<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/husfv7cel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="husfv7cel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:left-down-corner-arrow" /></template>
