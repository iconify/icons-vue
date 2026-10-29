<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p8u-xw6ko.css';
import '../../css/s/szbd9si1d.css';
import '../../css/w/wpz-cpbzk.css';
import '../../css/m/m6i-bjqet.css';
import '../../css/v/vgssyxiqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p8u-xw6ko wm-k"/><path class="szbd9si1d wm-a"/><path class="wm-shadow wpz-cpbzk"/><path class="m6i-bjqet wm-k"/><path class="vgssyxiqi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indent-increase-engrave" /></template>
