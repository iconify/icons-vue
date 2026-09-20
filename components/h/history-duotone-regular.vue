<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2jrt__gd"/><path class="ufppdlbpv"/><path class="cnjb-4b2j"/><path class="dp4augblj"/><path class="kv86m5bsi"/><path class="pfpu_3ppl"/><path class="dm5ccobgo"/><path class="mcj52c2nx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:history-duotone-regular" /></template>
<style>
.cnjb-4b2j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dm5ccobgo {
  d: path("M12 12h4");
}

.dp4augblj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3a9 9 0 1 1 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kv86m5bsi {
  d: path("M3 4v5h5");
}

.mcj52c2nx {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

.n2jrt__gd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4v5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.ufppdlbpv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
