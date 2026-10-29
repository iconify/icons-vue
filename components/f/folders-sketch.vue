<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wzo0eonru.css';
import '../../css/z/zeta229ez.css';
import '../../css/j/ji9_5zm4p.css';
import '../../css/u/ums7zcadz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wzo0eonru"/><path class="wm-a zeta229ez"/><path class="ji9_5zm4p wm-k"/><path class="ums7zcadz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folders-sketch" /></template>
