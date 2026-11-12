<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap4fu7vn.css';
import '../../css/m/mex95lw7c.css';
import '../../css/m/mcdgwguil.css';
import '../../css/h/hh45kun6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wap4fu7vn"/><path class="mex95lw7c"/><path class="mcdgwguil"/><path class="hh45kun6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-containers-lxc-light" /></template>
