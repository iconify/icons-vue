<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fvkv7bqef.css';
import '../../css/c/c7comr-ql.css';
import '../../css/y/y95393_dl.css';
import '../../css/i/i83y3y1nc.css';
import '../../css/o/o-cyv-b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fvkv7bqef"/><path class="c7comr-ql wm-shadow"/><path class="y95393_dl"/><path class="i83y3y1nc"/><path class="o-cyv-b7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-zap-engrave" /></template>
