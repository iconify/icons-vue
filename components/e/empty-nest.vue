<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uz4h91-er.css';
import '../../css/s/sk4gnbcgv.css';
import '../../css/r/rzbduwrtc.css';
import '../../css/w/w8ngsjbsw.css';
import '../../css/l/lxi5ubckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="uz4h91-er"/><path class="sk4gnbcgv"/><path clip-rule="evenodd" class="rzbduwrtc"/><path clip-rule="evenodd" class="w8ngsjbsw"/><path clip-rule="evenodd" class="lxi5ubckp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:empty-nest" /></template>
