<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiaedibfv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dca2urprn.css';
import '../../css/t/t-hhzbcli.css';
import '../../css/n/np8nxgbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xiaedibfv"/><g class="dt0cm9dhy primary"><path class="dca2urprn"/><path class="t-hhzbcli"/><path class="np8nxgbar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:doorbell-duo" /></template>
