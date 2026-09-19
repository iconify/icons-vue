<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwhm3z0ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cwhm3z0ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-play" /></template>
