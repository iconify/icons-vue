<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/syb471bdu.css';
import '../../css/i/iv9pp7bql.css';
import '../../css/i/i36oxtb3i.css';
import '../../css/w/waxdr2c7j.css';
import '../../css/a/a4bj_923c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="syb471bdu"/><path class="iv9pp7bql wm-k"/><path class="i36oxtb3i wm-a"/><path class="waxdr2c7j wm-k"/><path class="a4bj_923c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flag-sketch" /></template>
