<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw9-n0btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vw9-n0btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-with-taxi-checkerboard" /></template>
