<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0iy8x-ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0iy8x-ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-pause-solid" /></template>
