<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k05n1gbkm.css';
import '../../css/l/l5mq601jg.css';
import '../../css/g/gj4bohb8h.css';
import '../../css/y/yb_2z2bjb.css';
import '../../css/c/cadzq6bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":317};
const content = `<defs><linearGradient id="SVGBZt9de6J" x1="4%" x2="75.9%" y1="27%" y2="52.9%"><stop offset="0%"/><stop offset="100%" class="k05n1gbkm"/></linearGradient></defs><path class="l5mq601jg"/><path class="gj4bohb8h"/><path class="yb_2z2bjb"/><path fill="url(#SVGBZt9de6J)" class="cadzq6bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flutter" /></template>
