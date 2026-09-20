<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pubfbmb7r.css';
import '../../css/p/p_8skf9pq.css';
import '../../css/f/f_qs10cpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pubfbmb7r"/><path class="p_8skf9pq"/><path class="f_qs10cpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-heart-sharp-duotone" /></template>
