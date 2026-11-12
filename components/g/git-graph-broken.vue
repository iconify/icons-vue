<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fx_rppbll"/><path class="ua_8dab4r"/><path class="fn1p5fm9f"/><path class="tlj5bqbki"/><path class="s76sj2w-u"/><path class="a05t5w7og"/><path class="ev9kz4bik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-graph-broken" /></template>
<style>
.a05t5w7og {
  d: path("M12 22L12 9.07201");
}

.ev9kz4bik {
  d: path("M12 5.05145L12 2.00002");
}

.fn1p5fm9f {
  d: path("M22 5C22 6.65686 20.6569 8 19 8C17.3431 8 16 6.65686 16 5C16 3.34315 17.3431 2 19 2C20.6569 2 22 3.34315 22 5Z");
}

.fx_rppbll {
  d: path("M18.6236 11.59C18.1455 13.6055 17.2371 15.0984 16 16.0354");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s76sj2w-u {
  d: path("M5 16.0039L5 7.99999");
}

.tlj5bqbki {
  d: path("M8 19.0354C8 20.6923 6.65685 22.0354 5 22.0354C3.34315 22.0354 2 20.6923 2 19.0354C2 17.3785 3.34315 16.0354 5 16.0354C6.65685 16.0354 8 17.3785 8 19.0354Z");
}

.ua_8dab4r {
  d: path("M8 5C8 6.65685 6.65685 8 5 8C3.34315 8 2 6.65685 2 5C2 3.34315 3.34315 2 5 2C6.65685 2 8 3.34315 8 5Z");
}

</style>
