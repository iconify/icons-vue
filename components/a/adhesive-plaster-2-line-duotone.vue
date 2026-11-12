<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a-waiwrfa"/><path class="dd9euwbpb"/><path class="vw3528bnl"/><path class="arihl3bdb"/><path class="lii0jv5qd"/><path class="ghqgw0btr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:adhesive-plaster-2-line-duotone" /></template>
<style>
.a-waiwrfa {
  d: path("M20.4155 20.4155C18.3029 22.5282 14.8777 22.5282 12.765 20.4155L3.58447 11.235C1.47184 9.12233 1.47184 5.69709 3.58447 3.58447C5.69709 1.47184 9.12233 1.47184 11.235 3.58447L20.4155 12.765C22.5282 14.8777 22.5282 18.3029 20.4155 20.4155Z");
}

.arihl3bdb {
  stroke-linejoin: round;
  d: path("M9.17188 12H9.17197");
}

.dd9euwbpb {
  d: path("M12.7646 20.4155L20.415 12.7651M11.2345 3.58447L3.58398 11.235");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ghqgw0btr {
  stroke-linejoin: round;
  d: path("M14.8281 12H14.8282");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lii0jv5qd {
  stroke-linejoin: round;
  d: path("M12 14.8286H12.0001");
}

.vw3528bnl {
  stroke-linejoin: round;
  d: path("M12 9.17139H12.0001");
}

</style>
