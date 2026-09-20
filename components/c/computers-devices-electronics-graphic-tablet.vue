<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgwq21n2c.css';
import '../../css/g/g4las-uut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lgwq21n2c"/><path class="g4las-uut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-graphic-tablet" /></template>
