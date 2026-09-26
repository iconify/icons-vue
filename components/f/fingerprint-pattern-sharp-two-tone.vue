<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pb7h27bge"/><path class="r2mxfxb3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fingerprint-pattern-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pb7h27bge {
  stroke-opacity: 0.4;
  d: path("M4.2922 6.2471L4.9079 5.459C6.6135 3.2759 9.2296 2 12 2L13 2M20.9417 13.0067L20.8263 14C20.7091 15.0095 20.5327 16.0112 20.2982 17L20.0675 17.973M16.2613 8.1998L16.6359 9.127C16.8764 9.7222 17 10.3581 17 11C17 11.6677 16.9696 12.3351 16.9089 13L16.818 13.9959M12 10L12 11C12 15.0294 10.5687 18.9278 7.9615 22L7.662 22.3529");
}

.r2mxfxb3h {
  d: path("M15.1042 2.4933L16 2.9377C18.7417 4.298 20.6042 6.9584 20.9443 10L21.0062 10.5538M3 11.0002L3 11C3 10.581 3.0293 10.1624 3.0876 9.7474L3.2268 8.7572M3.2776 19.7454L3.9443 19C5.9121 16.7999 7 13.9517 7 11C7 8.2386 9.2386 6 12 6C12.5833 6 13.162 6.1021 13.7101 6.3015L14.6498 6.6436M16.4387 16.0379L16.166 17C15.6706 18.7475 14.9607 20.427 14.0526 22L13.7639 22.5");
}

</style>
