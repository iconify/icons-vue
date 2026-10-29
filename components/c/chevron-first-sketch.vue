<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h7c3qx-ae.css';
import '../../css/u/uwi6pe5sg.css';
import '../../css/p/p_w6bcb-q.css';
import '../../css/r/rj25d81vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h7c3qx-ae wm-k"/><path class="uwi6pe5sg wm-a"/><path class="p_w6bcb-q wm-k"/><path class="rj25d81vo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-first-sketch" /></template>
