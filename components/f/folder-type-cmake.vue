<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGDou8VdgE" x1="15.912" x2="21.015" y1="25.739" y2="14.942" gradientUnits="userSpaceOnUse"><stop offset="0" class="oo2kl4rdk"/><stop offset="1" class="fd1cb390p"/></linearGradient><linearGradient id="SVG2y1wodTS" x1="20.675" x2="27.799" y1="17.727" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset="0" class="f1nbas2bw"/><stop offset="1" class="oq8n5-bdi"/></linearGradient><linearGradient id="SVGkZWw4cmr" x1="24.797" x2="14.718" y1="28.981" y2="28.135" gradientUnits="userSpaceOnUse"><stop offset="0" class="badiqhb3e"/><stop offset="1" class="tk-5n3jhk"/></linearGradient><linearGradient id="SVG5G4Ygciw" x1="19.472" x2="19.342" y1="26.291" y2="21.908" gradientUnits="userSpaceOnUse"><stop offset="0" class="nz401ub3w"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="kin1yccsc"/><path fill="url(#SVGDou8VdgE)" class="imqpkmbcg"/><path class="zk2v-c7hm"/><path fill="url(#SVG2y1wodTS)" class="fzt0u-umz"/><path class="d1ij2sbey"/><path fill="url(#SVGkZWw4cmr)" class="wh48r7bfx"/><path class="oda-b3t7f"/><path fill="url(#SVG5G4Ygciw)" class="m6xahcbww"/><path class="tobtd8b_x"/><path class="k70qsoqdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cmake" /></template>
<style>
.badiqhb3e {
  stop-color: var(--svg-color--01a300, #01a300);
}

.d1ij2sbey {
  d: path("m31 30.982l-.061-.024l-8.981-3.658v-.016l-1.483-17.193l.047-.013Zm-8.995-3.722l8.89 3.627l-10.359-20.67Z");
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.f1nbas2bw {
  stop-color: var(--svg-color--b40e0e, #b40e0e);
}

.fd1cb390p {
  stop-color: var(--svg-color--6969e1, #6969e1);
}

.fzt0u-umz {
  d: path("M21.981 27.277L20.5 10.089l10.446 20.846Z");
}

.imqpkmbcg {
  d: path("m21.453 21.2l-11.391 9.733L20.5 10.091Z");
}

.k70qsoqdi {
  d: path("M30.884 31.075H10.092A.2.2 0 0 1 9.937 31a.18.18 0 0 1 .018-.171l10.425-20.82a.15.15 0 0 1 .121-.083a.13.13 0 0 1 .112.08l10.425 20.811a.2.2 0 0 1 .016.186a.19.19 0 0 1-.17.072m-20.807-.153h20.845q-.001-.009-.018-.036L20.5 10.109L10.09 30.893Z");
}

.kin1yccsc {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M27.9 6h-9.8l-2 4H5v17h25V6Zm.1 4h-7.8l1-2H28Z");
}

.m6xahcbww {
  d: path("m16.849 25.138l4.6-3.922l.64 6.056Z");
}

.nz401ub3w {
  stop-color: var(--svg-color--848484, #848484);
}

.oda-b3t7f {
  d: path("M30.957 30.958H10l.051-.044l6.771-5.814l.015.006l14.13 5.808Zm-20.825-.051h20.7l-14-5.754Z");
}

.oo2kl4rdk {
  stop-color: var(--svg-color--1011a1, #1011a1);
}

.oq8n5-bdi {
  stop-color: var(--svg-color--ff5959, #ff5959);
}

.tk-5n3jhk {
  stop-color: var(--svg-color--01df00, #01df00);
}

.tobtd8b_x {
  d: path("m22.147 27.351l-.077-.033l-5.316-2.165l.062-.053l4.673-3.984l.01.095Zm-5.2-2.229l5.087 2.072l-.621-5.879Z");
}

.wh48r7bfx {
  d: path("m16.827 25.124l14.13 5.809H10.065Z");
}

.zk2v-c7hm {
  d: path("m10.078 30.951l-.038-.029L20.518 10l.007.089l.954 11.122l-.009.008Zm10.4-20.77L10.14 30.833l11.287-9.644Z");
}

</style>
