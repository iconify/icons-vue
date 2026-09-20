<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="ssz630tqb"/><path class="y31290icy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:abl-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ssz630tqb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.75 7.002h-1.5L7 17h1.5l1.162-2.5h4.635L15.5 17H17zM13.726 13h-3.491L12 9z");
}

.y31290icy {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.5 17.298c-1.035.196-1.991 1.161-2.187 2.202H6.687c-.196-1.04-1.153-2.005-2.187-2.203V6.704C5.534 6.505 6.491 5.54 6.687 4.5h10.625c.196 1.04 1.153 2.005 2.188 2.202zm.337-11.196a1.935 1.935 0 0 1-1.927-1.939a.16.16 0 0 0-.162-.163H6.252a.16.16 0 0 0-.162.163a1.936 1.936 0 0 1-1.928 1.939a.16.16 0 0 0-.162.163v11.47c0 .09.072.163.162.163c1.064 0 1.928.87 1.928 1.939c0 .09.072.163.162.163h11.495c.09 0 .163-.073.163-.163c0-1.07.865-1.939 1.927-1.939c.09 0 .163-.072.163-.163V6.265a.17.17 0 0 0-.047-.115a.16.16 0 0 0-.116-.048");
}

</style>
