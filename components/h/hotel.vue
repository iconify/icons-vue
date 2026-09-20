<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="z3m6bxb9z"/><path class="ebb7bmupt"/><path class="njpd3yb4u"/><path class="endr2xb9j"/><path class="hfuwsq6zp"/><path class="qf58abbql"/><path class="i_44ajaeo"/><path class="m5r4yl6md"/><path class="odpke_lil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hotel" /></template>
<style>
.ebb7bmupt {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M36 6a4 4 0 0 1-4 4H20a4 4 0 0 1-4-4V5a4 4 0 0 1 4-4h12a4 4 0 0 1 4 4z");
}

.endr2xb9j {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M2 32h12v4H2zm0-6h16v4H2z");
}

.hfuwsq6zp {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M16 5v31h18a2 2 0 0 0 2-2V5z");
}

.i_44ajaeo {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M22 7h2v24h-2zm6 0h2v24h-2z");
}

.m5r4yl6md {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M22 32h8v4h-8zM10 14v4H6v-4H4v10h2v-4h4v4h2V14z");
}

.njpd3yb4u {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M0 12v22a2 2 0 0 0 2 2h31V12z");
}

.odpke_lil {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M7 25h2v6H7zm7 0h2v6h-2z");
}

.qf58abbql {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M18 20h16v4H18zm0-6h16v4H18zm0-6h16v4H18zm0 18h16v4H18z");
}

.z3m6bxb9z {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M21 15a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-3a4 4 0 0 1 4-4h13a4 4 0 0 1 4 4z");
}

</style>
