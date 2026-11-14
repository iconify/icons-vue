<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="web33s9uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bone-tag" /></template>
<style>
.web33s9uo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.75Q8.75 3.75 8.75 7q0 2.85 2.5 3.201V13H7.798q-.059-.727-.493-1.384q-.699-1.056-1.942-1.293q-1.244-.237-2.282.49q-1.037.726-1.24 1.976t.55 2.267q.183.247.395.444q-.212.197-.395.444q-.754 1.018-.55 2.267q.203 1.25 1.24 1.976q1.038.727 2.282.49t1.942-1.293q.434-.657.493-1.384h8.404q.059.727.493 1.384q.699 1.056 1.942 1.293q1.244.237 2.282-.49q1.037-.726 1.24-1.976t-.55-2.267q-.183-.247-.395-.444q.212-.197.395-.444q.754-1.018.55-2.267q-.203-1.25-1.24-1.976q-1.038-.727-2.282-.49t-1.942 1.293q-.434.657-.493 1.384H12.75v-2.799q2.5-.351 2.5-3.201q0-3.25-3.25-3.25");
}

</style>
