<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pghbxnbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cleared-to-land" /></template>
<style>
.pghbxnbmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.504 14.217l-.744.089a1.5 1.5 0 0 1-.93-.19l-1.651-.953a1.5 1.5 0 0 0-1.47-.018l-4.427 2.421a1.5 1.5 0 0 1-1.47-.017l-.136-.078a.773.773 0 0 1-.163-1.212l2.506-2.539a1.062 1.062 0 0 0-.225-1.666l-.602-.348a1.5 1.5 0 0 0-1.233-.12l-1.398.476a1.1 1.1 0 0 1-.907-.089a.404.404 0 0 1-.098-.621l1.849-2.047a1.5 1.5 0 0 0 .315-.544l.848-2.624a.404.404 0 0 1 .586-.226a1.1 1.1 0 0 1 .53.74L7.971 6.1a1.5 1.5 0 0 0 .721 1.008l.602.347a1.062 1.062 0 0 0 1.555-.638l.946-3.44a.773.773 0 0 1 1.131-.464l.136.079a1.5 1.5 0 0 1 .75 1.264l.117 5.044a1.5 1.5 0 0 0 .75 1.264l1.651.954a1.5 1.5 0 0 1 .63.71l.294.689a.938.938 0 0 1-.75 1.3M2.5 20.5H11m3.75-2.5l2 2L21 15.75");
}

</style>
