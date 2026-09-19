<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wghhn2b4n.css';
import '../../css/u/u3npkshsu.css';
import '../../css/g/gx_g0cb7y.css';
import '../../css/g/gg0ah_btc.css';
import '../../css/n/nyhdtzkrj.css';
import '../../css/o/od2s8-bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wghhn2b4n"/><path class="u3npkshsu"/><path class="gx_g0cb7y"/><path class="gg0ah_btc"/><path class="nyhdtzkrj"/><path class="od2s8-bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:calendar" /></template>
