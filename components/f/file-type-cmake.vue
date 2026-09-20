<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGCgNrzdsa" x1="9.955" x2="16.68" y1="9.096" y2="23.324" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="oo2kl4rdk"/><stop offset="1" class="fd1cb390p"/></linearGradient><linearGradient id="SVGrgqtQcHo" x1="16.231" x2="25.618" y1="19.655" y2="3.782" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="f1nbas2bw"/><stop offset="1" class="oq8n5-bdi"/></linearGradient><linearGradient id="SVGV3I43cHR" x1="21.663" x2="8.381" y1="4.823" y2="5.938" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="badiqhb3e"/><stop offset="1" class="tk-5n3jhk"/></linearGradient><linearGradient id="SVGhUomfdFs" x1="14.643" x2="14.472" y1="8.368" y2="14.145" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="nz401ub3w"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path fill="url(#SVGCgNrzdsa)" class="f2wxh1boq"/><path class="qbowwdntg"/><path fill="url(#SVGrgqtQcHo)" class="w9uudaczd"/><path class="bsbheyytt"/><path fill="url(#SVGV3I43cHR)" class="vk48albbe"/><path class="smhdir_1c"/><path fill="url(#SVGhUomfdFs)" class="y1fj5xbvj"/><path class="iw7jq8j6v"/><path class="fihc4mbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cmake" /></template>
<style>
.badiqhb3e {
  stop-color: var(--svg-color--01a300, #01a300);
}

.bsbheyytt {
  d: path("m29.818 29.8l-.061-.025l-11.828-4.827v-.015L15.975 2.282l.047-.013Zm-11.842-4.887L29.715 29.7L16.036 2.408Z");
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.f1nbas2bw {
  stop-color: var(--svg-color--b40e0e, #b40e0e);
}

.f2wxh1boq {
  d: path("M17.257 16.919L2.246 29.749L15.994 2.283Z");
}

.fd1cb390p {
  stop-color: var(--svg-color--6969e1, #6969e1);
}

.fihc4mbev {
  d: path("M29.7 29.911H2.285a.22.22 0 0 1-.182-.088a.22.22 0 0 1 .022-.2L15.864 2.187a.17.17 0 0 1 .14-.1a.15.15 0 0 1 .13.085l13.733 27.435a.24.24 0 0 1 .02.226a.21.21 0 0 1-.187.078m-27.468-.16l.057.011h27.4l.073-.009a.2.2 0 0 0-.028-.077L16 2.248v.012L2.261 29.684a.3.3 0 0 0-.025.067Z");
}

.iw7jq8j6v {
  d: path("m18.149 25l-.077-.032l-6.978-2.842l6.194-5.283l.01.094Zm-6.865-2.9l6.748 2.749l-.824-7.8Z");
}

.nz401ub3w {
  stop-color: var(--svg-color--848484, #848484);
}

.oo2kl4rdk {
  stop-color: var(--svg-color--1011a1, #1011a1);
}

.oq8n5-bdi {
  stop-color: var(--svg-color--ff5959, #ff5959);
}

.qbowwdntg {
  d: path("m2.262 29.768l-.038-.03L16.012 2.193l.008.088l1.263 14.649l-.01.008ZM15.977 2.374L2.324 29.649L17.23 16.908Z");
}

.smhdir_1c {
  d: path("M29.781 29.773H2.183l.051-.044l8.921-7.665l.014.006l18.622 7.655Zm-27.464-.05h27.337l-18.489-7.6Z");
}

.tk-5n3jhk {
  stop-color: var(--svg-color--01df00, #01df00);
}

.vk48albbe {
  d: path("m11.16 22.094l18.621 7.654H2.25Z");
}

.w9uudaczd {
  d: path("M17.952 24.931L16 2.28l13.767 27.471Z");
}

.y1fj5xbvj {
  d: path("m11.189 22.112l6.059-5.168l.843 7.98Z");
}

</style>
