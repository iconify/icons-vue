<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnaf7qbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xnaf7qbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:funeral-home" /></template>
