<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u14zawbne.css';
import '../../css/r/rw-ct3bfq.css';
import '../../css/k/kidl1_b4u.css';
import '../../css/y/yl7a92tqe.css';
import '../../css/o/okp7pp4nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u14zawbne wm-k"/><path class="rw-ct3bfq wm-s"/><path class="kidl1_b4u wm-shadow"/><path class="wm-k yl7a92tqe"/><path class="okp7pp4nk wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-minus-engrave" /></template>
