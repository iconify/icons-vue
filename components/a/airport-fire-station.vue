<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh_g2jbqm"/><path class="l-btu2sun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airport-fire-station" /></template>
<style>
.l-btu2sun {
  d: path("M3.25 18.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9.404-.572q-.045-.129-.108-.248q-.064-.12-.145-.229q-.081-.108-.178-.203t-.208-.174q-.11-.078-.232-.139q-.121-.061-.25-.102t-.263-.062T11 16.5q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088t-.138.102t-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167q-.017.084-.026.169t-.008.172q0 .086.008.172t.026.169q.016.085.041.167t.058.162t.074.155t.088.147q.048.072.102.138q.055.067.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026Q10.914 20 11 20q.185 0 .367-.039q.181-.039.35-.115q.169-.075.318-.185q.15-.11.273-.248M3.5 3.5h10v2.75h-10Zm3.5 0v2.75m3-2.75v2.75m8.5 8.25v7m-3-2.5l3-2.25l3 2.25M17 21.5h3");
}

.oh_g2jbqm {
  d: path("M14.157 16.5H2.5V10q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 9h11v1.5h4l1.192 1.192m1.626 1.626l.182.182v2.043");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
