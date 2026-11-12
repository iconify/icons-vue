<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0zmozbrc.css';
import '../../css/v/vpuku1byn.css';
import '../../css/t/t5qrcwbma.css';
import '../../css/k/k9zx-td9x.css';
import '../../css/q/q4ehtuwde.css';
import '../../css/c/c3fwvdbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG4HWR5bVF" x1="42.8" x2="239.5" y1="133.1" y2="505" gradientUnits="userSpaceOnUse"><stop offset="0" class="o0zmozbrc"/><stop offset="1" class="vpuku1byn"/></linearGradient><path fill="url(#SVG4HWR5bVF)" class="t5qrcwbma"/><linearGradient id="SVGRci2QbTY" x1="401" x2="215.1" y1="22" y2="531.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="k9zx-td9x"/><stop offset="1" class="q4ehtuwde"/></linearGradient><path fill="url(#SVGRci2QbTY)" class="c3fwvdbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kbin" /></template>
