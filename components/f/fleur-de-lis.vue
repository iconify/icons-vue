<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq4w-tbtk.css';
import '../../css/l/lea_bji6i.css';
import '../../css/j/jho4wkblq.css';
import '../../css/y/y6984pvoi.css';
import '../../css/h/h0wzrgb0q.css';
import '../../css/g/gs-g304kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGzJZyOdnU" cx="80.2" cy="68.8" r="124.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="wq4w-tbtk"/><stop offset=".85" class="lea_bji6i"/><stop offset="1" class="lea_bji6i"/></radialGradient></defs><path class="jho4wkblq"/><path fill="url(#SVGzJZyOdnU)" transform="matrix(2.8 0 0 2.8 -25.335 -25.335)" class="y6984pvoi"/><path class="h0wzrgb0q"/><path class="gs-g304kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:fleur-de-lis" /></template>
