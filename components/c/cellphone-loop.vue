<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="raphvibhn"/><path clip-rule="evenodd" class="cjxzckb3x"/><path clip-rule="evenodd" class="ao0s5jbtq"/><path clip-rule="evenodd" class="hnrh2411k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cellphone-loop" /></template>
<style>
.ao0s5jbtq {
  fill-rule: evenodd;
  d: path("M5.5 3.5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3H8A2.5 2.5 0 0 1 5.5 17v-.5a1 1 0 1 1 2 0v.5a.5.5 0 0 0 .5.5h7.5a1 1 0 0 0 1-1v-13a1 1 0 0 0-1-1h-7a1 1 0 0 0-1 1v2.25a1 1 0 0 1-2 0z");
}

.cjxzckb3x {
  fill-rule: evenodd;
  d: path("M12 14.963a.175.175 0 1 0 0 .35a.175.175 0 0 0 0-.35m-1.175.175a1.175 1.175 0 1 1 2.35 0a1.175 1.175 0 0 1-2.35 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hnrh2411k {
  fill-rule: evenodd;
  d: path("M7.347 9.38a2.193 2.193 0 1 0-2.567 3.555A2.193 2.193 0 0 0 7.347 9.38m-4.683-.677a4.193 4.193 0 1 1 1.827 6.342L2.4 17.942a1 1 0 1 1-1.622-1.17l2.091-2.897a4.195 4.195 0 0 1-.205-5.172");
}

.raphvibhn {
  d: path("M12.675 15.138a.675.675 0 1 1-1.35 0a.675.675 0 0 1 1.35 0");
}

</style>
