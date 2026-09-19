<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_q0b82j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sl_q0b82j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:angles-left" /></template>
