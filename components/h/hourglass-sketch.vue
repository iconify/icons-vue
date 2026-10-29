<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s7s6vmbwl.css';
import '../../css/v/v2qy5c52w.css';
import '../../css/i/i98n4_7xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s7s6vmbwl"/><path class="v2qy5c52w"/><path class="i98n4_7xh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hourglass-sketch" /></template>
