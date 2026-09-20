<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vlfm7vbmw.css';
import '../../css/i/im2t2g6ti.css';
import '../../css/r/r4y1ovbns.css';
import '../../css/c/cz7b21b0u.css';
import '../../css/a/awgmcr9_g.css';
import '../../css/i/i0i0lwbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="vlfm7vbmw"/><rect class="im2t2g6ti"/><rect transform="rotate(90 11 13)" class="r4y1ovbns"/><rect class="cz7b21b0u"/><path class="awgmcr9_g"/><path class="i0i0lwbsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:gamepad" /></template>
