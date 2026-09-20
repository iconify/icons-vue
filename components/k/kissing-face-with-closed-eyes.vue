<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGJOv7obCd" cx="64" cy="-568" r="56.96" fx="64" fy="-568" gradientTransform="matrix(1 0 0 -1 0 -504)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".919" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGx3WvQbrG" cx="14.898" cy="267.446" r="23.667" fx="14.898" fy="267.446" gradientTransform="matrix(.97908 0 0 .93012 15.876 -176.51)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="xxl2uvnsa"/><stop offset=".197" class="popcf8e5b"/><stop offset=".474" class="l8y_lcbgu"/><stop offset=".845" class="a44b3qwyn"/><stop offset="1" class="he1ha19dv"/></radialGradient><radialGradient id="SVGlGAiVdRg" cx="83.408" r="23.667" fx="83.408" href="#SVGx3WvQbrG"/></defs><path fill="url(#SVGJOv7obCd)" class="uuo0vn6ns"/><path class="km4-lkoid"/><path class="wa4qcbcln"/><circle fill="url(#SVGx3WvQbrG)" class="tdmhzqb0h"/><circle fill="url(#SVGlGAiVdRg)" class="v_v15ugcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:kissing-face-with-closed-eyes" /></template>
<style>
.a44b3qwyn {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.098;
}

.he1ha19dv {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0;
}

.km4-lkoid {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.893 30.769C117.22 39.366 120 49.612 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.063 0-37.037-7.347-48.179-22.94C24.583 111.623 44.811 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.742-3.471-24.06-10.107-33.231");
}

.l8y_lcbgu {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.314;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.popcf8e5b {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.449;
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.tdmhzqb0h {
  cx: 30.462px;
  cy: 72.247px;
  r: 23.096px;
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.v_v15ugcc {
  cx: 97.538px;
  cy: 72.247px;
  r: 23.096px;
}

.wa4qcbcln {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M49.134 60.13c-1.612-2.03-4.016-4.12-6.78-4.102l.168-.003c-2.447-.126-4.87 1.69-6.336 3.384l-.57.64c-1.171 1.612-3.487 1.976-4.996.616c-2.42-2.372-.358-5.37 1.363-7.907c2.094-2.941 6.458-5.348 10.371-5.253c5.762-.05 11.043 4.28 12.618 9.484c1.18 3.507-3.607 6.023-5.838 3.14m43.328.001c-1.611-2.03-4.016-4.12-6.78-4.102l.168-.003c-2.447-.126-4.869 1.69-6.336 3.384c-.362.408-.57.64-.57.64c-1.17 1.612-3.486 1.976-4.996.616c-2.423-2.41-.361-5.342 1.364-7.907c2.093-2.942 6.458-5.348 10.37-5.253c5.763-.05 11.044 4.28 12.619 9.484c1.18 3.508-3.608 6.023-5.839 3.14m-19.606 25.9s2.86-2.324 3.05-5.864c.192-3.609-.729-4.841-1.906-6.413c-2.758-3.68-10.45-2.777-10.447-2.778c-2.056.074-4.448 1.06-4.153 3.44c.131 1.062 1.412 2.355 2.872 2.706c3.033.73 7.368.014 7.489 3.09c.136 3.464-5.178 2.042-5.604 5.701s5.605 3.187 5.601 5.71c-.003 1.931-1.978 2.263-4.069 2.696c-1.788.37-5.228.93-5.505 2.986s.901 4.57 5.743 3.837c7.618-1.154 10.17-5.318 10.17-7.882c0-4.805-3.241-7.23-3.241-7.23M47.383 33.711c2.309.03 2.977-3.129.532-3.65c-1.832-.365-3.841-.417-5.829-.169c-5.57.613-10.371 3.476-13.503 7.218c-1.562 1.92.994 3.937 2.693 2.508c4.35-3.532 10.094-5.863 16.107-5.907m32.864.679c-2.294.257-3.27-2.82-.887-3.579c1.788-.543 3.782-.792 5.784-.74c5.603.063 10.662 2.441 14.146 5.857c1.744 1.759-.602 4.016-2.433 2.76c-4.677-3.087-10.621-4.843-16.61-4.297");
}

.xxl2uvnsa {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.5;
}

</style>
