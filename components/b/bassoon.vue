<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpgmrccco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bassoon" /></template>
<style>
.wpgmrccco {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 9.724q-4.39-.318-4.497-4.512L3.857 2.886q-.077-.128-.099-.276q-.022-.147.014-.292q.037-.145.125-.264q.089-.12.217-.197q.063-.038.133-.063t.143-.036t.146-.007q.074.003.146.021t.138.05q.067.031.126.075q.06.044.109.099q.05.055.088.118l1.5 2.5q.107.178.107.386q0 2.907 3 3.214V5.25q.002-2.499 2.5-2.499t2.5 2.498V17.87l1.206 3.378q.025.069.036.142t.007.147t-.022.146q-.018.071-.049.138t-.076.126q-.044.059-.099.109q-.054.05-.118.088q-.063.037-.133.062q-.122.044-.252.044h-6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 21.5q0-.13.044-.252L9.75 17.87z");
}

</style>
