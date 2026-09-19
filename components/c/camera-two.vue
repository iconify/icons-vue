<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mv4as3bxi.css';
import '../../css/o/os7-ocikw.css';
import '../../css/h/hot4egbds.css';
import '../../css/q/qq9gmxdgs.css';
import '../../css/z/zqs1pywbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="mv4as3bxi"/><path class="os7-ocikw"/><path class="hot4egbds"/><circle class="qq9gmxdgs"/><circle class="zqs1pywbv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:camera-two" /></template>
