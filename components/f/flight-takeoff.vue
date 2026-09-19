<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr8jhsbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xr8jhsbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:flight-takeoff" /></template>
