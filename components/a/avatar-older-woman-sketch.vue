<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o8xh_lbvg.css';
import '../../css/h/h5hpoq8kp.css';
import '../../css/z/z8twodclj.css';
import '../../css/w/weicl-k-p.css';
import '../../css/r/rwx0oacsc.css';
import '../../css/y/y7dx3bbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o8xh_lbvg wm-k"/><path class="h5hpoq8kp wm-k"/><path class="wm-k z8twodclj"/><path class="weicl-k-p wm-a"/><path class="rwx0oacsc wm-s"/><path class="wm-k y7dx3bbtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-older-woman-sketch" /></template>
