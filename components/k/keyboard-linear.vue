<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="klim778ja"/><path class="unjje161g"/><path class="kpkzq8p6g"/><path class="zwiw2-bkv"/><path class="ca53wpbej"/><path class="g3w7qrfpr"/><path class="bkm8bzboi"/><path class="nyj0vvxdk"/><path class="r70kn_d9i"/><path class="km0rz_boi"/><path class="glttn3bpw"/><path class="ics6c5abb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:keyboard-linear" /></template>
<style>
.bkm8bzboi {
  stroke-linejoin: round;
  d: path("M18 9H18.0001");
}

.ca53wpbej {
  stroke-linejoin: round;
  d: path("M12 9H12.0001");
}

.g3w7qrfpr {
  stroke-linejoin: round;
  d: path("M15 9H15.0001");
}

.glttn3bpw {
  stroke-linejoin: round;
  d: path("M9 12H9.0001");
}

.ics6c5abb {
  stroke-linejoin: round;
  d: path("M6 12H6.0001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klim778ja {
  d: path("M8 19H16C18.8284 19 20.2426 19 21.1213 18.1213C22 17.2426 22 15.8284 22 13V11C22 8.17157 22 6.75736 21.1213 5.87868C20.2426 5 18.8284 5 16 5H8C5.17157 5 3.75736 5 2.87868 5.87868C2 6.75736 2 8.17157 2 11V13C2 15.8284 2 17.2426 2.87868 18.1213C3.75736 19 5.17157 19 8 19Z");
}

.km0rz_boi {
  stroke-linejoin: round;
  d: path("M12 12H12.0001");
}

.kpkzq8p6g {
  stroke-linejoin: round;
  d: path("M6 9H6.0001");
}

.nyj0vvxdk {
  stroke-linejoin: round;
  d: path("M18 12H18.0001");
}

.r70kn_d9i {
  stroke-linejoin: round;
  d: path("M15 12H15.0001");
}

.unjje161g {
  d: path("M7 16H17");
}

.zwiw2-bkv {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
}

</style>
