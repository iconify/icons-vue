<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy6ubfbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6ubfbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ev-station-filled" /></template>
