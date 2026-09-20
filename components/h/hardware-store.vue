<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t60evox7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="t60evox7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:hardware-store" /></template>
