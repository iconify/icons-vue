<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng84t3-ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ng84t3-ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:add-playlist" /></template>
