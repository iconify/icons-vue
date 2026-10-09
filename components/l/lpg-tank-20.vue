<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ro5gmkv.css';
import '../../css/k/kbep-sbgp.css';
import '../../css/k/km0u10_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y7ro5gmkv"/><path class="kbep-sbgp"/><path class="km0u10_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lpg-tank-20" /></template>
