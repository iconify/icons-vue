<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y59_e3bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y59_e3bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:camera-off" /></template>
