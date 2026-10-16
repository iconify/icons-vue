<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny9vdpbbd.css';
import '../../css/k/ku2rlub5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny9vdpbbd"/><path class="ku2rlub5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chisel-20" /></template>
