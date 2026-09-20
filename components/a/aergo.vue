<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedAergo0)" class="kbvecd4ml"/><path fill="url(#tokenBrandedAergo1)" class="g7126ubvn"/><path fill="url(#tokenBrandedAergo2)" class="ivpccxb2t"/><path fill="url(#tokenBrandedAergo3)" class="x7jalvbmi"/><path class="bespi8bhy"/><path fill="url(#tokenBrandedAergo4)" class="m0fx-rb7p"/><path fill="url(#tokenBrandedAergo5)" class="bbgz-c96c"/><defs><linearGradient id="tokenBrandedAergo0" x1="27.917" x2="16.682" y1="14.688" y2="-4.575" gradientUnits="userSpaceOnUse"><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/></linearGradient><linearGradient id="tokenBrandedAergo1" x1="21.68" x2="18.377" y1="15.181" y2="4.074" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/><stop offset="1" class="v_ykgwbik"/></linearGradient><linearGradient id="tokenBrandedAergo2" x1="21.62" x2="18.42" y1="15.117" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/><stop offset="1" class="v_ykgwbik"/></linearGradient><linearGradient id="tokenBrandedAergo3" x1="22.98" x2="19.541" y1="15.612" y2="4.06" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/><stop offset="1" class="v_ykgwbik"/></linearGradient><linearGradient id="tokenBrandedAergo4" x1="10.954" x2="11.145" y1="22.029" y2="6.882" gradientUnits="userSpaceOnUse"><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/><stop offset="1" class="v_ykgwbik"/></linearGradient><linearGradient id="tokenBrandedAergo5" x1="14.642" x2="14.642" y1="15.15" y2="9.842" gradientUnits="userSpaceOnUse"><stop class="kz7b9dj2g"/><stop offset=".25" class="h2fvtu94d"/><stop offset=".76" class="ixuczfbhb"/><stop offset="1" class="v_ykgwbik"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aergo" /></template>
<style>
.bbgz-c96c {
  d: path("M15.584 13.892c-.067-.133-.159-.3-.263-.488l-.446-.791c-.058-.109-.537-.754-.625-1.421c-.041-.354.05-.709.25-.992l-.641-.679a2.17 2.17 0 0 0-.521 1.763c.083.866.658 1.6.696 1.666l.445.792l.313.567c.167.3.267.466.275.816h.904a2.4 2.4 0 0 0-.383-1.233z");
}

.bespi8bhy {
  fill: var(--svg-color--ff33b2, #FF33B2);
  d: path("M15.396 9.78c.32.003.63.137.862.374a1.25 1.25 0 0 1-.104 1.784l.613.641a2.22 2.22 0 0 0 .687-1.22A2.097 2.097 0 0 0 14.8 8.962c-.354.1-.68.291-.942.558l.642.68c.108-.138.25-.25.404-.322c.154-.07.321-.104.492-.1");
}

.ft5dv1b6b {
  fill: none;
}

.g7126ubvn {
  d: path("M19.917 8.875a1.98 1.98 0 0 0-1.45.588a2.2 2.2 0 0 0-.634 1.496c.024.556.255 1.083.646 1.479a2.03 2.03 0 0 0 1.438.604a2.03 2.03 0 0 0 1.437-.604a2.24 2.24 0 0 0 .646-1.48a2.2 2.2 0 0 0-.633-1.495a2 2 0 0 0-1.45-.584zm0 3.334a1.25 1.25 0 1 1 0-2.5c.67 0 1.233.483 1.25 1.25c.016.766-.571 1.25-1.25 1.25");
}

.h2fvtu94d {
  stop-color: var(--svg-color--a9a9a9, #A9A9A9);
}

.ivpccxb2t {
  d: path("M9.5 11.93c-.23.197-.53.298-.833.279c-.338 0-.646-.213-.834-.417l2.917-1.15v-.013a2.2 2.2 0 0 0-.73-1.27a2 2 0 0 0-1.34-.484a2 2 0 0 0-1.46.588a2.2 2.2 0 0 0-.637 1.496c.013.562.241 1.097.638 1.495a2.09 2.09 0 0 0 2.896.021zm-2.083-.859c0-.783.575-1.375 1.25-1.362c.345 0 .791.208 1.02.479zc0 .033 0-.03 0 0");
}

.ixuczfbhb {
  stop-color: var(--svg-color--595959, #595959);
}

.kbvecd4ml {
  d: path("M13.138 8.896a1.8 1.8 0 0 0-1.434.408a1.78 1.78 0 0 0-.537 1.342v2.396H12v-2.408a.88.88 0 0 1 .684-.896c.191-.05.375-.021.566-.004v-.821z");
}

.kz7b9dj2g {
  stop-color: var(--svg-color--d2d2d2, #D2D2D2);
}

.m0fx-rb7p {
  d: path("m16.767 12.584l-.613-.646c-.08.07-.158.137-.25.196c-.33.187-.67.35-1.03.479l-.837.337l-.166.067c-.463.183-1.234.483-1.642 1.05a1.83 1.83 0 0 0-.404 1.058h.904c.013-.25.096-.325.234-.537c.25-.35.891-.6 1.237-.734l.28-.112l.84-.338c.35-.146.697-.316 1.026-.508q.227-.131.416-.312z");
}

.v_ykgwbik {
  stop-color: var(--svg-color--393939, #393939);
}

.x7jalvbmi {
  d: path("M6.167 10.959a2.2 2.2 0 0 0-.634-1.492a1.98 1.98 0 0 0-1.45-.592a1.98 1.98 0 0 0-1.45.588A2.2 2.2 0 0 0 2 10.959c.012.56.238 1.096.633 1.495a2 2 0 0 0 1.45.584l1.213-.009h.87zm-.834 1.25h-1.25a1.25 1.25 0 0 1-1.25-1.25c0-.709.542-1.263 1.25-1.25a1.295 1.295 0 0 1 1.25 1.25z");
}

</style>
