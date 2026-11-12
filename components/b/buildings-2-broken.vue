<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="z-dxw3bya"/><path class="suhy-dbax"/><path class="cchpq1djo"/><path class="x-21zwayg"/><path class="bd1q7zbzn"/><path class="pm28f0dxx"/><path class="aysaofbup"/><path class="f5spxzclx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-2-broken" /></template>
<style>
.aysaofbup {
  d: path("M14 8H13.5M11.5 8H10");
}

.bd1q7zbzn {
  d: path("M10 5H14");
}

.cchpq1djo {
  d: path("M6.5 8C5.09554 8 4.39331 8 3.88886 8.33706C3.67048 8.48298 3.48298 8.67048 3.33706 8.88886C3 9.39331 3 10.0955 3 11.5V16M3 20V22");
}

.f5spxzclx {
  d: path("M10 11H14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pm28f0dxx {
  d: path("M10 14H10.5M12.5 14H14");
}

.suhy-dbax {
  d: path("M17.5 8C18.9045 8 19.6067 8 20.1111 8.33706C20.3295 8.48298 20.517 8.67048 20.6629 8.88886C21 9.39331 21 10.0955 21 11.5M21 15.5V22");
}

.x-21zwayg {
  d: path("M12 22V19");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

.z-dxw3bya {
  d: path("M17 22V6C17 4.11438 17 3.17157 16.4142 2.58579C15.8284 2 14.8856 2 13 2H11C9.11438 2 8.17157 2 7.58579 2.58579C7 3.17157 7 4.11438 7 6V22");
}

</style>
