<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipy_s6bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diplomatic-pouch" /></template>
<style>
.ipy_s6bdp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.736 8.606q.585.263 1.09.719q-.085-.041-.177-.06q-.093-.019-.187-.014t-.185.033t-.17.077l-5.879 3.618q-.749-.729-2.228-.729t-2.228.729L3.893 9.361q-.08-.049-.17-.077t-.185-.033q-.094-.005-.187.014q-.092.019-.177.06q.505-.456 1.09-.719q.173-2.442 2.529-3.9Q8.943 3.375 12 3.375t5.207 1.331q2.356 1.458 2.529 3.9m-10.65 5.712l-5.979-3.679q-.127-.078-.215-.199q-.087-.121-.122-.266q-.03-.126-.016-.255t.071-.245Q1.75 10.864 1.75 12.5v5q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5v-5q0-1.636-1.075-2.826q.057.116.071.245t-.016.255q-.035.145-.122.266q-.088.121-.215.199l-5.979 3.679q.086.423.086.932q0 3-3 3t-3-3q0-.509.086-.932M6 8.25h12q.098 0 .194.004Q17.657 4.875 12 4.875T5.806 8.254Q5.902 8.25 6 8.25");
}

</style>
