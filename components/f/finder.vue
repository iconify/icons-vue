<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8x_tthfa.css';
import '../../css/t/tgotzmt5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8x_tthfa"/><path class="tgotzmt5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:finder" /></template>
