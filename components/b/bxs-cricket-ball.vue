<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybps4ubau.css';
import '../../css/s/sh39ly0gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybps4ubau"/><path class="sh39ly0gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-cricket-ball" /></template>
