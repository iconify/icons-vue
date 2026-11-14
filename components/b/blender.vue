<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rons6xbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blender" /></template>
<style>
.rons6xbqu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.375Q6.25 2.375 6.25 5q0 .105.029.206t.084.19t.133.16t.172.117q-.224.553-.117 1.197l1 6q.052.313.149.574q-1.95.616-1.95 3.181v2.25q0 3.375 3.375 3.375h5.75q3.375 0 3.375-3.375v-2.25q0-2.565-1.95-3.181q.097-.261.149-.574l1-6q.107-.644-.117-1.197q.094-.047.172-.117t.133-.16t.084-.19T17.75 5q0-2.625-5.75-2.625M12.01 17q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 17z");
}

</style>
