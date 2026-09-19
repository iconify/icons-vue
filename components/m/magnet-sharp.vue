<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r11mf4_ss.css';
import '../../css/y/ydudqy-kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r11mf4_ss"/><path class="ydudqy-kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:magnet-sharp" /></template>
