<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG70DvXcmC)" class="m8c14nb_d"/><defs><linearGradient id="SVG70DvXcmC" x1="11.04" x2="11.12" y1="3" y2="20.71" gradientUnits="userSpaceOnUse"><stop class="xawtaybfq"/><stop offset=".54" class="l_3qguzbk"/><stop offset=".8" class="b65jfnp2o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fcon" /></template>
<style>
.b65jfnp2o {
  stop-color: var(--svg-color--46f7b0, #46f7b0);
}

.ft5dv1b6b {
  fill: none;
}

.l_3qguzbk {
  stop-color: var(--svg-color--26baf8, #26baf8);
}

.m8c14nb_d {
  d: path("M14.5 5.19L12 3L9.5 5.19v6.593l1.344 1.26l.68-.73l-1.025-.96V5.64L12 4.33l1.5 1.31v5.711l-5 4.699v-5.547l-.85.85a.5.5 0 0 0-.15.355v6.652l7.002-6.577zm1.851 6.167a.5.5 0 0 1 .15.35v6.637l-3.941-3.62l.68-.74l2.26 2.08v-5.562l.851.85zM12 15.204l-.5.465v4.87L12 21l.5-.46v-4.871l-.5-.46zm-2.5 2.4l1-.915v3.13l-.8-.735a.6.6 0 0 1-.2-.445zm5-.04l-1-.98v3.3l.81-.74c.125-.12.19-.28.19-.45z");
}

.xawtaybfq {
  stop-color: var(--svg-color--6167fb, #6167fb);
}

</style>
