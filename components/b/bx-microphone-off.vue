<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua71p0bsg.css';
import '../../css/l/lnske1bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua71p0bsg"/><path class="lnske1bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-microphone-off" /></template>
