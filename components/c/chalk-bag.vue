<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2w325bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chalk-bag" /></template>
<style>
.f2w325bxp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.899 3.75h2.202q-.283-.562-1.101-.562t-1.101.562m3.794 0h.291q1.105 0 1.66.956t.007 1.916l-.568.994q-.051.09-.107.173Q20.75 11.437 20.75 16q0 6.25-8.75 6.25T3.25 16q0-4.563 4.774-8.211q-.056-.083-.107-.173l-.568-.994q-.548-.96.007-1.916t1.66-.956h.291Q9.645 1.688 12 1.688t2.693 2.062");
}

</style>
