<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woxg0sbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="woxg0sbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-right-long" /></template>
