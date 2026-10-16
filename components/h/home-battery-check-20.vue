<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxr384btv.css';
import '../../css/m/mf8_0-bsn.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hxr384btv"/><path class="mf8_0-bsn"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-check-20" /></template>
