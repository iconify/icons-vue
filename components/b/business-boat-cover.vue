<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pngau5c0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:business-boat-cover" /></template>
<style>
.pngau5c0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 14.75h5.892q1.212 0 1.799 1.06t-.055 2.088l-.736 1.177q-.734 1.175-2.12 1.175H6.47q-1.386 0-2.12-1.176l-.736-1.176q-.642-1.028-.055-2.088t1.799-1.06h5.892v-12q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q11.926 2 12 2t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm5.538-12.192l3 1.25q.103.042.189.113q.085.071.147.163t.094.199q.032.106.032.217v2.25q0 2.709-3.455 4.189Q18.154 11 18 11t-.295-.061Q14.25 9.459 14.25 6.75V4.5q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25Q17.85 2.5 18 2.5t.288.058M10.75 11.5V8.75q.001-1.499-1.437-1.924t-2.252.835l-1.697 2.622q-.725 1.121-.087 2.294T7.25 13.75H8.5q2.25 0 2.25-2.25");
}

</style>
