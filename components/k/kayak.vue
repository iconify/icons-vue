<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6w1uhbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kayak" /></template>
<style>
.f6w1uhbrj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.646 10.299q-3.531 3.658-6.809 9.85q-.043.081-.065.17t-.022.181t.022.181t.065.17q.035.065.081.122q.047.058.104.105t.122.082t.135.057t.145.029q.073.008.147.001q.073-.007.144-.028t.136-.056q4.739-2.509 7.995-5.167Q9.5 15.875 9.5 12q0-.968.146-1.701m2.506-2.293q1.068.082 1.746 1.34q.602 1.119.602 2.654q0 .992-.251 1.809q3.587-3.675 6.914-9.958q.043-.081.065-.17t.022-.181t-.022-.181t-.065-.17q-.035-.065-.081-.122q-.047-.058-.104-.105t-.122-.082t-.135-.057q-.071-.022-.145-.029q-.073-.008-.147-.001q-.073.007-.144.028t-.136.056q-4.741 2.51-7.997 5.169");
}

</style>
