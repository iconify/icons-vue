<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVG266lbtRN)" class="mkoduxtac"/></g><defs><linearGradient id="SVG266lbtRN" x1="4" x2="19.86" y1="19.003" y2="5.968" gradientUnits="userSpaceOnUse"><stop class="g9790lcds"/><stop offset=".37" class="w7dqnvawf"/><stop offset=".65" class="f100ehoot"/><stop offset=".86" class="ip-98lbei"/><stop offset="1" class="hr1k6kb1p"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cell-background" /></template>
<style>
.f100ehoot {
  stop-color: var(--svg-color--3ce9ff, #3ce9ff);
}

.ft5dv1b6b {
  fill: none;
}

.g9790lcds {
  stop-color: var(--svg-color--964bff, #964bff);
}

.hr1k6kb1p {
  stop-color: var(--svg-color--ffff21, #ffff21);
}

.ip-98lbei {
  stop-color: var(--svg-color--caff2c, #caff2c);
}

.mkoduxtac {
  d: path("M7.825 19.003a.66.66 0 0 1-.66-.65a.66.66 0 0 1 1.32 0c0 .354-.3.65-.66.65m5.405-.826a.66.66 0 1 1 1.32 0a.66.66 0 0 1-1.32 0m2.46-.434v-.03a.573.573 0 1 1 1.145.03c0 .3-.25.55-.55.565h-.025a.57.57 0 0 1-.565-.566zm-6.2-.39a.84.84 0 0 1-.83-.83a.835.835 0 0 1 1.67 0c0 .455-.375.83-.835.83zm-3.115-.265a.75.75 0 0 1-.725-.74a.75.75 0 0 1 1.495 0a.75.75 0 0 1-.77.74m11.825-.085a.486.486 0 0 1-.485-.48a.485.485 0 0 1 .965 0a.48.48 0 0 1-.48.48m-10.86-2.74a.925.925 0 1 1 1.85 0a.925.925 0 0 1-1.85 0m11.87.435a.395.395 0 0 1 .79 0a.4.4 0 0 1-.79 0m-13.76.304a.84.84 0 0 1-.835-.824a.835.835 0 1 1 1.67 0c0 .45-.375.824-.835.824m1.19-3.174a1.01 1.01 0 1 1 2.02 0a1.01 1.01 0 0 1-2.02 0m-2.64 0a.925.925 0 1 1 1.85 0a.925.925 0 0 1-1.85 0m3.34-2.435a.925.925 0 1 1 1.85 0a.925.925 0 0 1-1.85 0m-1.89.914a.84.84 0 0 1-.835-.824a.835.835 0 0 1 1.67 0c0 .45-.375.824-.835.824m13.755-.914a.4.4 0 0 1 .795 0a.4.4 0 0 1-.79 0zM9.5 8.223a.835.835 0 0 1-.835-.83a.835.835 0 1 1 1.67 0c0 .45-.375.83-.835.83m-3.12-.09a.75.75 0 0 1-.725-.74a.75.75 0 0 1 1.495 0a.75.75 0 0 1-.77.74m11.825-.085a.485.485 0 0 1-.485-.48a.485.485 0 0 1 .965 0a.48.48 0 0 1-.48.48M15.7 6.263v-.03a.57.57 0 0 1 1.14.015a.57.57 0 0 1-.162.405a.57.57 0 0 1-.978-.39m-2.465-.35a.66.66 0 1 1 1.32 0a.66.66 0 0 1-1.32 0m-5.405.395a.66.66 0 0 1-.66-.65a.66.66 0 1 1 1.32 0c0 .355-.3.65-.66.65m4.67 11.445a.75.75 0 1 1-1.499 0a.75.75 0 0 1 1.499 0m-1.25-2.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m-.25-3.25a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m.25-1.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5m2.25 1.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-1.75-4.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w7dqnvawf {
  stop-color: var(--svg-color--a695ff, #a695ff);
}

</style>
