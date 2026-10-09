<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1sn-9bjn.css';
import '../../css/f/fpex59k2x.css';
import '../../css/y/y0i4r3btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z1sn-9bjn"/><path class="fpex59k2x"/><path class="y0i4r3btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lpg-tank-20-bold" /></template>
