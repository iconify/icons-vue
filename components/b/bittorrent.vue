<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4t60l8ox.css';
import '../../css/h/hwnfhubeq.css';
import '../../css/h/hsyfdwbne.css';
import '../../css/g/g9z0_ccaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4t60l8ox"/><path class="hwnfhubeq"/><path class="hsyfdwbne"/><path class="g9z0_ccaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bittorrent" /></template>
