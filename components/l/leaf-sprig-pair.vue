<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-l5lz-yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-sprig-pair" /></template>
<style>
.f-l5lz-yr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.316 13.744L5.53 21.53q-.105.106-.243.163T5 21.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.389-3.389q-1.905-1.599-2.821-4.344q-1.069-3.207-.266-6.419q.037-.145.125-.264q.089-.12.217-.197t.276-.099q.147-.022.292.014q.1.025.19.077q2.874 1.642 3.965 4.914q.644 1.933.475 3.865l1.944-1.944q.113-3.113 2.464-5.464q2.469-2.47 5.78-2.47q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 3.311-2.47 5.78q-2.351 2.351-5.464 2.464");
}

</style>
