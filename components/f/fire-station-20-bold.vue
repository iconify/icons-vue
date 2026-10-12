<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prssdsbsb.css';
import '../../css/p/p90oggben.css';
import '../../css/i/i59ju7bdr.css';
import '../../css/y/y77ro9r-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prssdsbsb"/><path class="p90oggben"/><path class="i59ju7bdr"/><path class="y77ro9r-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-station-20-bold" /></template>
