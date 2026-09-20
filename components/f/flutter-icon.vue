<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":284};
const content = `<defs><radialGradient id="SVGXxQ1kd1i" cx="2.814%" cy="6.818%" r="151.475%" fx="2.814%" fy="6.818%" gradientTransform="matrix(1 0 0 .8077 0 .013)"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></radialGradient><linearGradient id="SVGL0EyQbrD" x1="19.657%" x2="69.874%" y1="81.493%" y2="47.643%"><stop offset="0%" class="f6_qqdbgp"/><stop offset="100%" class="lxwwh9bvz"/></linearGradient></defs><path class="yjrw36bkb"/><path class="ih5oy6b9l"/><path fill="url(#SVGL0EyQbrD)" class="jzttojbpm"/><path class="hqucz-bmc"/><path fill="url(#SVGXxQ1kd1i)" class="r86oflq6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:flutter-icon" /></template>
<style>
.dk8d3t44m {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.1;
}

.f6_qqdbgp {
  stop-color: var(--svg-color--1a237e, #1a237e);
  stop-opacity: 0.4;
}

.hqucz-bmc {
  fill: var(--svg-color--29b6f6, #29b6f6);
  d: path("m108.982 163.478l-43.586 43.585l43.586 43.586l43.585-43.586z");
}

.ih5oy6b9l {
  fill: var(--svg-color--01579b, #01579b);
  d: path("m108.988 250.67l32.693 32.693h87.187l-76.295-76.277z");
}

.jzttojbpm {
  d: path("m108.988 250.67l64.658-22.383l-21.073-21.201z");
}

.lxwwh9bvz {
  stop-color: var(--svg-color--1a237e, #1a237e);
  stop-opacity: 0;
}

.r86oflq6v {
  d: path("m228.868 130.79l-76.277 76.277l76.277 76.296h-87.187l-32.693-32.693l-43.602-43.603l76.295-76.278zM141.681 0L0 141.681l43.603 43.603L228.868 0z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.yjrw36bkb {
  fill: var(--svg-color--54c5f8, #54c5f8);
  d: path("M228.864 130.789h-87.187l-76.278 76.296l43.585 43.584zM43.603 185.284L0 141.681L141.681 0h87.187z");
}

</style>
