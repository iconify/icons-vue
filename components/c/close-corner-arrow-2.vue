<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssip8gfhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ssip8gfhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:close-corner-arrow-2" /></template>
