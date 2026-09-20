<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGrYbJOcMb" cx="64" cy="64" r="56.96" fx="64" fy="64" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".919" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVG9WxtveNf" cx="15.821" cy="117.259" r="23.029" fx="15.821" fy="117.259" gradientTransform="matrix(.97908 0 0 .93012 15.876 -30.44)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="xxl2uvnsa"/><stop offset=".197" class="popcf8e5b"/><stop offset=".474" class="l8y_lcbgu"/><stop offset=".845" class="a44b3qwyn"/><stop offset="1" class="he1ha19dv"/></radialGradient><radialGradient id="SVGQWpT8yFL" cx="82.485" fx="82.485" href="#SVG9WxtveNf"/></defs><path fill="url(#SVGrYbJOcMb)" class="uuo0vn6ns"/><path class="km4-lkoid"/><circle fill="url(#SVG9WxtveNf)" class="ky6_ccbdf"/><circle fill="url(#SVGQWpT8yFL)" class="gr77uqbfh"/><path class="k9hx3plgv"/><path class="ovh5m8muv"/><path class="ojeq89bth"/><ellipse class="gki671xbe"/><path class="k3-fwibvw"/><ellipse class="b8dcvtq3q"/><path class="byij9db1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:flushed-face" /></template>
<style>
.a44b3qwyn {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.098;
}

.b8dcvtq3q {
  cx: 39.15px;
  cy: 61.2px;
  fill: var(--svg-color--422b0d, #422b0d);
  rx: 7.5px;
  ry: 7.6px;
}

.byij9db1d {
  fill: var(--svg-color--896024, #896024);
  d: path("M39.498 56.875c-1.033-.717-2.578-.494-3.581.953s-.671 2.972.362 3.689c1.033.716 2.577.494 3.581-.954s.67-2.972-.362-3.688m50.162 0c-1.034-.717-2.578-.494-3.582.953s-.67 2.972.363 3.689c1.033.716 2.577.494 3.58-.954c1.005-1.448.671-2.972-.362-3.688");
}

.gki671xbe {
  cx: 89.65px;
  cy: 61.3px;
  fill: var(--svg-color--422b0d, #422b0d);
  rx: 7.5px;
  ry: 7.6px;
}

.gr77uqbfh {
  cx: 96.635px;
  cy: 78.626px;
  r: 22.474px;
}

.he1ha19dv {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0;
}

.k3-fwibvw {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.15 43.8c9.6 0 17.4 7.8 17.4 17.4s-7.8 17.4-17.4 17.4s-17.4-7.8-17.4-17.4s7.9-17.4 17.4-17.4");
}

.k9hx3plgv {
  fill: var(--svg-color--35220b, #35220b);
  d: path("M72.9 101.1h-17a4 4 0 0 1 0-8h17a4 4 0 0 1 0 8");
}

.km4-lkoid {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.893 30.769C117.22 39.366 120 49.612 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.063 0-37.037-7.347-48.179-22.94C24.583 111.623 44.811 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.742-3.471-24.06-10.107-33.231");
}

.ky6_ccbdf {
  cx: 31.365px;
  cy: 78.626px;
  r: 22.474px;
}

.l8y_lcbgu {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.314;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.ojeq89bth {
  fill: var(--svg-color--fff, #fff);
  d: path("M89.65 43.9c9.6 0 17.4 7.8 17.4 17.4s-7.8 17.4-17.4 17.4s-17.4-7.8-17.4-17.4s7.9-17.4 17.4-17.4");
}

.ovh5m8muv {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("m46.926 27.446l.1.006c2.183.342 3.282-2.693.932-3.547c-1.764-.615-3.747-.945-5.749-.974c-5.601-.164-10.753 2.007-14.372 5.28c-1.813 1.685.44 4.036 2.32 2.856c4.797-2.896 10.808-4.41 16.77-3.621m34.947 0l-.1.006c-2.183.342-3.282-2.693-.932-3.547c1.764-.615 3.747-.945 5.749-.974c5.601-.164 10.753 2.007 14.372 5.28c1.813 1.685-.44 4.036-2.32 2.856c-4.797-2.896-10.808-4.41-16.77-3.621");
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

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.xxl2uvnsa {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.5;
}

</style>
