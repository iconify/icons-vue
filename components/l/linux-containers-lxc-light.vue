<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap4fu7vn.css';
import '../../css/m/m85zrbbfy.css';
import '../../css/y/y1178jbwh.css';
import '../../css/l/l_u0qmb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wap4fu7vn"/><path class="m85zrbbfy"/><path class="y1178jbwh"/><path class="l_u0qmb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linux-containers-lxc-light" /></template>
