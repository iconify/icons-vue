<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2_an0cdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dewdrop" /></template>
<style>
.j2_an0cdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.223 19.716Q2.564 11.376 6.97 6.97q4.498-4.499 13.098-3.717q.065.006.128.023t.122.045t.113.065t.099.084t.084.099q.037.054.065.113t.045.122t.023.128q.782 8.6-3.717 13.098q-4.406 4.406-12.746 3.747L3.03 22.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113zM12.6 8.3q-.064-.086-.15-.15q-.059-.044-.126-.076q-.066-.032-.138-.051q-.071-.018-.145-.022t-.147.007t-.143.034q-.07.025-.133.063q-.064.037-.119.087T11.4 8.3l-2.25 3q-.043.058-.075.123q-.784 1.619.171 3.143T12 16.09t2.754-1.524t.171-3.143q-.032-.065-.075-.123z");
}

</style>
