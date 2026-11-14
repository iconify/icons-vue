<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyv0i0bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heartburn" /></template>
<style>
.dyv0i0bvs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 6.757V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q10.074 1.75 10 1.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v5.375l-.7.525q-.07.052-.126.119t-.095.146t-.059.163T8.25 9q0 2.75-1.25 2.75q-3.25 0-3.25 3.25q0 2.656 2.002 4.436Q7.793 21.25 11 21.25q3.806 0 6.433-2.312q2.817-2.479 2.817-6.438q0-4.874-4.013-6.212q-3.228-1.076-5.487.469m3.738 3.174q2.762 2.367 2.762 4.569q0 3.25-3.25 3.25t-3.25-3.25q0-1.714 1.415-2.421q.139-.07.295-.078t.302.046q.121-1.144.595-1.933q.038-.063.088-.118t.108-.099q.06-.044.127-.075q.066-.032.138-.05t.146-.021q.073-.004.146.007t.143.036t.133.063q.054.032.102.074");
}

</style>
