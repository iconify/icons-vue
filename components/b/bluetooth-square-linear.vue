<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/om59y67-s.css';
import '../../css/h/hyyb83bqk.css';
import '../../css/p/pw8f5c0fp.css';
import '../../css/s/si3inpc3v.css';
import '../../css/i/i70bgdbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="om59y67-s"/><path class="hyyb83bqk"/><path class="pw8f5c0fp"/><path class="si3inpc3v"/><path class="i70bgdbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-square-linear" /></template>
