<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1bjxd59y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drone-outline-sharp" /></template>
<style>
.s1bjxd59y {
  fill: currentColor;
  d: path("M5 19q0-1.644.91-2.93q.91-1.285 2.361-1.787l-.423-3.667H4.981V6H2.019V5h6.923v1H5.981v3.616h1.738l-.103-1h8.75l-.104 1h1.719V6h-2.962V5h6.948v1h-2.961v4.616h-2.848l-.424 3.667q1.453.502 2.36 1.787Q19 17.356 19 19h-1q0-1.65-1.117-2.825T14.135 15H9.846q-1.611 0-2.729 1.175T6 19zm4.24-5h5.495l.502-4.384H8.719zm0 0h5.495z");
}

</style>
