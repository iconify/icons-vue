<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d3vy85bid"/><path class="xuwwn8b_h"/><path class="vq8-7y9te"/><path class="c2pqembzo"/><path class="yez4qekpl"/><path class="qob85vcfg"/><path class="uw6indbog"/><path class="xvqdltb2j"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-off-broken" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.c2pqembzo {
  d: path("M16.2986 3.3538C15.0813 2.5006 13.5988 2 11.9994 2C10.1716 2 8.49661 2.6538 7.19531 3.7403");
}

.d3vy85bid {
  d: path("M14.5 19.5H9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qob85vcfg {
  d: path("M14.5 19.5C14.5 20.4346 14.5 20.9019 14.299 21.25C14.1674 21.478 13.978 21.6674 13.75 21.799C13.4019 22 12.9346 22 12 22C11.0654 22 10.5981 22 10.25 21.799C10.022 21.6674 9.8326 21.478 9.701 21.25C9.5 20.9019 9.5 20.4346 9.5 19.5");
}

.uw6indbog {
  d: path("M12 17V15");
}

.vq8-7y9te {
  d: path("M17.7593 14.3041C18.8458 13.0028 19.4996 11.3277 19.4996 9.50003C19.4996 8.10673 19.1197 6.80223 18.4578 5.68433");
}

.xuwwn8b_h {
  d: path("M14.5 19.5001C14.5 18.7866 14.5 18.4298 14.5381 18.1931C14.6609 17.4297 14.6824 17.3816 15.1692 16.7808C15.2652 16.6623 15.5271 16.416 15.9938 15.9939");
}

.xvqdltb2j {
  d: path("M13.7324 14C13.3866 14.5978 12.7403 15 12 15C11.2597 15 10.6134 14.5978 10.2676 14");
}

.yez4qekpl {
  d: path("M5.5953 5.59521C4.9004 6.73261 4.5 8.06951 4.5 9.49991C4.5 11.7205 5.4651 13.7158 6.9988 15.0891C8.1195 16.0926 8.6799 16.5944 8.8308 16.7806C9.3176 17.3814 9.3391 17.4295 9.4619 18.1929C9.5 18.4296 9.5 18.7864 9.5 19.4999");
}

</style>
