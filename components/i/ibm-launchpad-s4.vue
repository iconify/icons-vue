<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcrs9-qzk.css';
import '../../css/r/rtwbx3bhp.css';
import '../../css/s/so8rb_4ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fcrs9-qzk"/><path class="rtwbx3bhp"/><path class="so8rb_4ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-launchpad-s4" /></template>
