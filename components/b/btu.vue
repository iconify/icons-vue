<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzsxfebud.css';
import '../../css/f/fmy9nacam.css';
import '../../css/f/fyqrbo7td.css';
import '../../css/d/dtzs14bot.css';
import '../../css/u/ur6v5_b8c.css';
import '../../css/b/bqiwrx_sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzsxfebud"/><path class="fmy9nacam"/><path class="fyqrbo7td"/><path class="dtzs14bot"/><path class="ur6v5_b8c"/><path class="bqiwrx_sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btu" /></template>
