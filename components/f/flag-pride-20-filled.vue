<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="tg7vxkxgp"/><path class="jr5po8b6a"/><path class="ymp1e4z1g"/><path class="k_zvbj-ir"/><path class="sg4_gwb5j"/><path class="r-v8hmbvy"/><path class="jzxoifmmu"/><path class="f0w6i3b4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-pride-20-filled" /></template>
<style>
.f0w6i3b4k {
  d: path("M3.5 3h13a.5.5 0 0 1 .5.5v8a.5.5 0 0 1-.5.5H4v5.5a.5.5 0 0 1-1 0v-14a.5.5 0 0 1 .5-.5zM4 4v7h12V4H4z");
  fill: var(--svg-color--212121, #212121);
}

.ft5dv1b6b {
  fill: none;
}

.jr5po8b6a {
  fill: var(--svg-color--e62c46, #E62C46);
  d: path("M4 5h12v1H4z");
}

.jzxoifmmu {
  fill: var(--svg-color--b73fbb, #B73FBB);
  d: path("M4 10h12v1H4z");
}

.k_zvbj-ir {
  fill: var(--svg-color--ffd23e, #FFD23E);
  d: path("M4 7h12v1H4z");
}

.r-v8hmbvy {
  fill: var(--svg-color--1793e8, #1793E8);
  d: path("M4 9h12v1H4z");
}

.sg4_gwb5j {
  fill: var(--svg-color--61bc51, #61BC51);
  d: path("M4 8h12v1H4z");
}

.tg7vxkxgp {
  fill: var(--svg-color--745125, #745125);
  d: path("M4 4h12v1H4z");
}

.ymp1e4z1g {
  fill: var(--svg-color--f36d38, #F36D38);
  d: path("M4 6h12v1H4z");
}

</style>
