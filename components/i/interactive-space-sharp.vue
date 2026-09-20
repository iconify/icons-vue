<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g88lu6bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:interactive-space-sharp" /></template>
<style>
.g88lu6bvd {
  fill: currentColor;
  d: path("m7 8.48l1.635-1.614L7 5.25L5.384 6.866zm9.5-1.21q.414 0 .707-.294t.293-.707t-.293-.706t-.707-.294t-.707.294t-.293.706t.293.707t.707.293M6 21.231v-1.408q0-.586.324-1.096t.874-.75q1.148-.517 2.348-.786T12 16.923t2.454.268t2.348.786q.55.24.874.75T18 19.823v1.408zm4.227-6.42q-.727-.726-.727-1.773t.727-1.773T12 10.538t1.773.727t.727 1.773t-.727 1.773t-1.773.727t-1.773-.727m-2.54-1.042H3v-11h18v11h-4.686q.053-.25.065-.5q.011-.25 0-.5q-.104-1.727-1.363-2.921T12 8.654T8.984 9.848T7.62 12.769q-.011.25 0 .5q.012.25.066.5");
}

</style>
