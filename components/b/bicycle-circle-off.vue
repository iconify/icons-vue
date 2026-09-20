<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="p_3hajbuh"/><path clip-rule="evenodd" class="v2ku1gblt"/><path class="zdcsv-b9y"/><path clip-rule="evenodd" class="ndjhhfdwm"/><path class="a6cixu_6g"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bicycle-circle-off" /></template>
<style>
.a6cixu_6g {
  d: path("m16.98 5.743l2.5 12.562c.261 1.308-1.7 1.698-1.96.39l-2.5-12.562c-.261-1.307 1.7-1.698 1.96-.39");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.ndjhhfdwm {
  fill-rule: evenodd;
  d: path("M7.5 19.5H13a1 1 0 0 0 .983-1.185l3.864-6.165A1 1 0 0 0 17 10.619h-5.55l-.802-2.432a1 1 0 0 0-1.9.627l1.007 3.047l-3.146 6.186A1 1 0 0 0 7.5 19.5m3.138-4.964L9.13 17.5h2.487zm2.536 1.303l2.019-3.22h-3.082z");
}

.p_3hajbuh {
  d: path("M16.062 6.936a1 1 0 1 1-.124-1.996C19.828 4.7 22 5.46 22 7.44c0 1.574-.978 2.274-2.855 2.55a1 1 0 1 1-.29-1.98C19.87 7.862 20 7.77 20 7.44c0-.296-1.094-.68-3.938-.504");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.v2ku1gblt {
  fill-rule: evenodd;
  d: path("M18.5 23a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-11 7a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

.zdcsv-b9y {
  d: path("M8 9.5a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2z");
}

</style>
