<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vq6d8hmfu.css';
import '../../css/g/gmkm8hbfw.css';
import '../../css/p/p8di0eziy.css';
import '../../css/r/r6592acqf.css';
import '../../css/w/wi2zf_h8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vq6d8hmfu"/><path class="gmkm8hbfw"/><path class="p8di0eziy"/><path class="r6592acqf"/><path class="wi2zf_h8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:globe-arrow" /></template>
