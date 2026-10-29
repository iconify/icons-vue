<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cvwtfk2zv.css';
import '../../css/r/r-0xcxboy.css';
import '../../css/p/plj1kabpx.css';
import '../../css/j/jqp01sc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cvwtfk2zv"/><path class="r-0xcxboy wm-a"/><path class="plj1kabpx wm-k"/><path class="jqp01sc5u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:info-circle-sketch" /></template>
