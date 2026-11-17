<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hkbd-tg1c"/><path class="hx_1lvbxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fan-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hkbd-tg1c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.486 9.331q.428.202.789.508a4.2 4.2 0 0 1 1.672-.388c.431-.011.863.034 1.288.1c.491.077.979.18 1.466.284a4 4 0 1 1-1.664 7.825c-.676-.144-1.337-.407-1.873-.853a4 4 0 0 1-.566-.588c-.214-.272-.394-.567-.596-.847a3.6 3.6 0 0 1-.835.429a4.2 4.2 0 0 1-.5 1.642c-.206.379-.461.73-.731 1.065a27 27 0 0 1-.978 1.127a4 4 0 0 1-2.763 1.318a3.998 3.998 0 0 1-3.182-6.671c.462-.513 1.021-.955 1.675-1.195q.386-.14.792-.196c.342-.05.689-.059 1.032-.093a3.6 3.6 0 0 1 .046-.937a4.2 4.2 0 0 1-1.172-1.254a7 7 0 0 1-.557-1.166a27 27 0 0 1-.487-1.411a4 4 0 1 1 7.608-2.472c.214.657.317 1.361.198 2.048a4 4 0 0 1-.226.785c-.129.321-.294.625-.436.94");
}

.hx_1lvbxm {
  d: path("M7.775 11.137a3.502 3.502 0 0 1 6.449 2.725a3.5 3.5 0 1 1-6.449-2.725m1.842 1.947a1.501 1.501 0 0 0 2.765-1.167a1.5 1.5 0 1 0-2.765 1.167");
}

</style>
