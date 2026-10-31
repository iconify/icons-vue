<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu4ch7b4k.css';
import '../../css/h/hshbphkqv.css';
import '../../css/j/ju50y3dul.css';
import '../../css/f/f2zgmfbez.css';
import '../../css/z/z0aj8yglb.css';
import '../../css/q/qf_qd1b4s.css';
import '../../css/m/m1-42ebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xu4ch7b4k"/><path class="hshbphkqv"/><path class="ju50y3dul"/><path class="f2zgmfbez"/><path class="z0aj8yglb"/><path class="qf_qd1b4s"/><path class="m1-42ebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:burrito" /></template>
