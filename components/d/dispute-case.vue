<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy6tn_nnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dispute-case" /></template>
<style>
.wy6tn_nnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.676 3.727l4.597 4.597q1.766 1.767.001 3.534l-1.416 1.415q-1.767 1.766-3.534.001l-1.768-1.769L4.53 19.53q-.105.106-.243.163T4 19.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l8.025-8.026l-1.768-1.768q-1.766-1.767-.001-3.534l1.416-1.415q1.767-1.766 3.534-.001zM12 16h8q2.25 0 2.25 2.25T20 20.5h-8q-2.25 0-2.25-2.25T12 16");
}

</style>
