<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tvw4qm_ug"/><rect class="mrvjhibls"/><path class="eo01bdc6e"/><rect class="hwts0fb9q"/><path class="sq_t8eryj"/><rect class="pbdkm4tie"/><path class="a4x-tibtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiobookshelf" /></template>
<style>
.a4x-tibtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.526 18.616h7.052m2.934-1.614C37.512 8.982 32.021 4.5 24 4.5S10.488 8.981 10.488 17.002m-.984 0h.984v9.513h0h-.984a3.263 3.263 0 0 1-3.262-3.262v-2.988a3.263 3.263 0 0 1 3.262-3.263m28.991 9.513h-.984h0v-9.513h.984a3.263 3.263 0 0 1 3.263 3.262v2.989a3.263 3.263 0 0 1-3.263 3.262");
}

.eo01bdc6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.422 18.616h7.052");
}

.hwts0fb9q {
  width: 7.052px;
  height: 26.896px;
  x: 20.474px;
  y: 13.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.655px;
}

.mrvjhibls {
  width: 7.052px;
  height: 26.896px;
  x: 13.422px;
  y: 13.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.655px;
}

.pbdkm4tie {
  width: 7.052px;
  height: 26.896px;
  x: 27.526px;
  y: 13.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.655px;
}

.sq_t8eryj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.474 18.616h7.052");
}

.tvw4qm_ug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.843 43.5h30.314");
}

</style>
