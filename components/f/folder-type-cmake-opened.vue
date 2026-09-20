<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGudEDSbpd" x1="15.915" x2="21.018" y1="25.739" y2="14.942" gradientUnits="userSpaceOnUse"><stop offset="0" class="oo2kl4rdk"/><stop offset="1" class="fd1cb390p"/></linearGradient><linearGradient id="SVGEVo7dc6F" x1="20.676" x2="27.799" y1="17.727" y2="29.772" gradientUnits="userSpaceOnUse"><stop offset="0" class="f1nbas2bw"/><stop offset="1" class="oq8n5-bdi"/></linearGradient><linearGradient id="SVG450IDdaN" x1="24.799" x2="14.72" y1="28.981" y2="28.135" gradientUnits="userSpaceOnUse"><stop offset="0" class="badiqhb3e"/><stop offset="1" class="tk-5n3jhk"/></linearGradient><linearGradient id="SVG33cT8GRM" x1="19.474" x2="19.345" y1="26.291" y2="21.908" gradientUnits="userSpaceOnUse"><stop offset="0" class="nz401ub3w"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="gmwlyf0zv"/><path class="o96ttg5yk"/><path fill="url(#SVGudEDSbpd)" class="n9lkgzb1b"/><path class="xi2p-pt1t"/><path fill="url(#SVGEVo7dc6F)" class="p3y3r-brm"/><path class="u1pe3e6fe"/><path fill="url(#SVG450IDdaN)" class="cxqxe3i1z"/><path class="i0zdo3bzo"/><path fill="url(#SVG33cT8GRM)" class="zxpc5ok9q"/><path class="z4qy1ibou"/><path class="g3i-kab5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cmake-opened" /></template>
<style>
.badiqhb3e {
  stop-color: var(--svg-color--01a300, #01a300);
}

.cxqxe3i1z {
  d: path("m16.829 25.124l14.131 5.809H10.068Z");
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

.g3i-kab5t {
  d: path("M30.887 31.075H10.094A.2.2 0 0 1 9.939 31a.19.19 0 0 1 .018-.171l10.426-20.82a.14.14 0 0 1 .12-.083a.14.14 0 0 1 .115.079l10.423 20.812a.2.2 0 0 1 .015.187a.19.19 0 0 1-.169.071m-20.808-.153h20.846q-.001-.009-.018-.037L20.5 10.109L10.092 30.893Zm-.016 0");
}

.gmwlyf0zv {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M27.9 6h-9.7l-2 4H5v17h25V6Zm.1 18H7V12h21Zm.1-14h-7.8l1-2H28Z");
}

.i0zdo3bzo {
  d: path("M30.96 30.958H10l.052-.044l6.772-5.814l.015.006l14.131 5.803Zm-20.825-.051h20.7l-14-5.754Z");
}

.n9lkgzb1b {
  d: path("m21.456 21.2l-11.391 9.733L20.5 10.091Z");
}

.nz401ub3w {
  stop-color: var(--svg-color--848484, #848484);
}

.o96ttg5yk {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M25.9 14H.3l3.8 13h25.6z");
}

.oo2kl4rdk {
  stop-color: var(--svg-color--1011a1, #1011a1);
}

.oq8n5-bdi {
  stop-color: var(--svg-color--ff5959, #ff5959);
}

.p3y3r-brm {
  d: path("M21.983 27.277L20.5 10.089l10.449 20.846Z");
}

.tk-5n3jhk {
  stop-color: var(--svg-color--01df00, #01df00);
}

.u1pe3e6fe {
  d: path("m31 30.982l-.062-.024L21.96 27.3v-.016l-1.485-17.193l.047-.013Zm-8.993-3.722l8.89 3.627l-10.361-20.67Z");
}

.xi2p-pt1t {
  d: path("m10.081 30.951l-.039-.029L20.518 10l.007.089l.957 11.122l-.009.008Zm10.4-20.77L10.143 30.833l11.287-9.644Z");
}

.z4qy1ibou {
  d: path("m22.149 27.351l-.077-.033l-5.316-2.165l.062-.053l4.673-3.984l.01.095Zm-5.2-2.229l5.087 2.072l-.621-5.879Z");
}

.zxpc5ok9q {
  d: path("m16.851 25.138l4.6-3.922l.64 6.056Z");
}

</style>
