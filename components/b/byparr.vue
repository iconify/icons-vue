<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh-bxob0v.css';
import '../../css/o/or6tflh7g.css';
import '../../css/w/wt5q0gb-i.css';
import '../../css/i/i-zynpbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jh-bxob0v"/><path class="or6tflh7g"/><path class="wt5q0gb-i"/><path class="i-zynpbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:byparr" /></template>
