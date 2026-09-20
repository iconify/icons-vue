<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGypVOXbVr)" class="r4i437pya"/><path clip-rule="evenodd" class="z38n-hbfx"/><path class="fpjy5p6cp"/><path class="ld25dsxos"/></g><defs><linearGradient id="SVGypVOXbVr" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="fn9t6ybkd"/><stop offset="1" class="i9xthacyd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grc-background" /></template>
<style>
.fn9t6ybkd {
  stop-color: var(--svg-color--7401e2, #7401e2);
}

.fpjy5p6cp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.97 11.212c-.316-1.58-1.43-2.718-2.687-3.603l-1.769.936c1.244.693 2.371 1.516 2.72 2.727h1.748zm-4.96-4.964c.572.313 1.202.657 1.818 1.054L12 8.268q-.345-.18-.686-.353a32 32 0 0 1-1.14-.599q.895-.571 1.83-1.07zm-.51-.28c-.358-.2-.68-.388-.942-.572c-.568.34-1.704 1.009-1.704.975c.227.236.52.456.854.668c.702-.447 1.15-.719 1.793-1.07m5.553 6.274H12l-.97 1.94h3.245c-.783.722-1.897 1.334-3.001 1.94c-.87.479-1.732.953-2.421 1.475c.568.33 1.704 1.018 1.704 1.035l.586-.324c2.522-1.388 5.777-3.18 5.91-6.066");
}

.ft5dv1b6b {
  fill: none;
}

.i9xthacyd {
  stop-color: var(--svg-color--41007f, #41007f);
}

.ld25dsxos {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.036 11.212c.506-2.53 3.055-3.922 4.962-4.964c.563-.308 1.07-.585 1.452-.852c.568.34 1.704 1.009 1.704.975c-.548.57-1.476 1.042-2.462 1.544c-1.94.988-4.105 2.09-4.028 4.27c.048 1.377 1.33 2.36 2.85 3.253c-.633.355-1.077.606-1.753.987c-1.792-1.303-3.176-2.956-2.725-5.213m3.165 5.522q.9-.51 1.803-1.015q.362.203.728.404c.365.2.728.4 1.077.602l-.263.168c-.539.346-.942.605-1.539.94a26 26 0 0 1-1.806-1.1m2.301 1.375l.361.199q.303.166.587.325c0-.018 1.136-.705 1.704-1.036a11 11 0 0 0-.89-.601l.006.01q-.246.155-.457.293q-.645.42-1.31.81");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.z38n-hbfx {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4.562L5.697 8.277v7.447L12 19.438l6.303-3.714V8.276zM18.788 8L12 4L5.212 8v8L12 20l6.788-4z");
}

</style>
