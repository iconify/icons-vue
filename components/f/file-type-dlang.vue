<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGcfgOxcXG" x1="185.455" x2="181.955" y1="1601.641" y2="1630.224" gradientTransform="translate(-62.523 -666.646)scale(.427)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="SVG5NB3weAE" x1="176.136" x2="172.636" y1="1600.5" y2="1629.083" href="#SVGcfgOxcXG"/></defs><path class="l58n7-v3y"/><path class="nu00s6s5l"/><path fill="url(#SVGcfgOxcXG)" class="e01b9j20v"/><path class="x9nq9ccgb"/><path fill="url(#SVG5NB3weAE)" class="upqcttb5x"/><path class="ub-8i_b_s"/><ellipse class="ewt106n6i"/><path class="l04tpjb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dlang" /></template>
<style>
.e01b9j20v {
  d: path("M20.993 18.979a7.9 7.9 0 0 1-2.128 2.582a9.7 9.7 0 0 1-3.256 1.71a11.6 11.6 0 0 1-1.971.472h-.015a32 32 0 0 1-3.326.111l-5.625.022a.616.616 0 0 1-.686-.681l-.01-7.734Q2.992 15.42 2 15.4V30h28v-9.456a85 85 0 0 0-8.59-2.6a7 7 0 0 1-.417 1.035");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ewt106n6i {
  cx: 26.78px;
  cy: 8.777px;
  fill: var(--svg-color--fff, #fff);
  rx: 1.374px;
  ry: 1.259px;
}

.l04tpjb6k {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.673 23.877l5.625-.022a32 32 0 0 0 3.326-.111h.015a11.5 11.5 0 0 0 1.971-.472a9.7 9.7 0 0 0 3.256-1.71a7.9 7.9 0 0 0 2.128-2.582a7 7 0 0 0 .417-1.034a7 7 0 0 0 .332-2.051a7 7 0 0 0-1.36-4.148a8 8 0 0 0-1.421-1.5a8.9 8.9 0 0 0-2.244-1.359a15.7 15.7 0 0 0-6.067-.95l-6.074.009h-.076a.59.59 0 0 0-.532.562l.009 6.952l.01 7.734a.616.616 0 0 0 .685.682m3.1-12.908h2.619a22 22 0 0 1 2.588.1a7.4 7.4 0 0 1 1.629.438a5.8 5.8 0 0 1 1.508.822a4.12 4.12 0 0 1 1.748 3.458a5 5 0 0 1-.175 1.327a4.46 4.46 0 0 1-1.518 2.271a5.6 5.6 0 0 1-1.187.748a7.7 7.7 0 0 1-1.628.5a16 16 0 0 1-2.877.2H7.786L7.78 15.7Z");
}

.l58n7-v3y {
  fill: var(--svg-color--b03931, #b03931);
  d: path("m3.978 15.462l-.009-6.953a.59.59 0 0 1 .531-.562h.076l6.074-.009a15.7 15.7 0 0 1 6.067.95a8.9 8.9 0 0 1 2.244 1.359a4.47 4.47 0 0 1 2.946-1.083a4.11 4.11 0 0 1 4.276 3.92A4.11 4.11 0 0 1 21.907 17c-.089 0-.177-.008-.265-.012a7 7 0 0 1-.232.953a85 85 0 0 1 8.59 2.6V2H2v13.4q.992.02 1.978.062m22.8-7.944a1.32 1.32 0 0 1 1.374 1.259a1.379 1.379 0 0 1-2.747 0a1.32 1.32 0 0 1 1.375-1.26Z");
}

.nu00s6s5l {
  fill: var(--svg-color--b03931, #b03931);
  d: path("M17.861 15.787a4.11 4.11 0 0 0-1.748-3.458a5.8 5.8 0 0 0-1.508-.822a7.4 7.4 0 0 0-1.629-.438a22 22 0 0 0-2.588-.1H7.769l.006 4.737a89 89 0 0 1 9.91 1.408a5 5 0 0 0 .176-1.327m3.132 3.192a7.9 7.9 0 0 1-2.128 2.582a9.7 9.7 0 0 1-3.256 1.71a11.6 11.6 0 0 1-1.971.472h-.015a32 32 0 0 1-3.326.111l-5.625.022a.616.616 0 0 1-.686-.681l-.01-7.734Q2.992 15.42 2 15.4V30h28v-9.456a85 85 0 0 0-8.59-2.6a7 7 0 0 1-.417 1.035");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.ub-8i_b_s {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.383 11.746a7 7 0 0 1 1.36 4.148a6.6 6.6 0 0 1-.1 1.1c.088 0 .176.012.265.012a4.11 4.11 0 0 0 4.276-3.92a4.11 4.11 0 0 0-4.276-3.92a4.47 4.47 0 0 0-2.946 1.083a8 8 0 0 1 1.421 1.497");
}

.upqcttb5x {
  d: path("M10.477 20.835a16 16 0 0 0 2.877-.2a7.6 7.6 0 0 0 1.628-.5a5.6 5.6 0 0 0 1.187-.748a4.46 4.46 0 0 0 1.518-2.271a89 89 0 0 0-9.91-1.408l.006 5.133Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x9nq9ccgb {
  fill: var(--svg-color--b03931, #b03931);
  d: path("M10.477 20.835a16 16 0 0 0 2.877-.2a7.6 7.6 0 0 0 1.628-.5a5.6 5.6 0 0 0 1.187-.748a4.46 4.46 0 0 0 1.518-2.271a89 89 0 0 0-9.91-1.408l.006 5.133Z");
}

</style>
