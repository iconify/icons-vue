<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g5dvq_klh.css';
import '../../css/p/p68pgcbjk.css';
import '../../css/l/lzad66der.css';
import '../../css/s/sc6ko9v-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g5dvq_klh"/><path class="p68pgcbjk wm-a"/><path class="lzad66der wm-k"/><path class="sc6ko9v-k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cherry-sketch" /></template>
