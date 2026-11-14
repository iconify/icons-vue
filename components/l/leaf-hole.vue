<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-xkwkoco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-hole" /></template>
<style>
.u-xkwkoco {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.502 18.437q.086-7.21 4.155-11.28Q12.814 3 20.25 3q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 7.436-4.157 11.593q-4.07 4.069-11.28 4.155L4.28 20.78q-.105.106-.243.163T3.75 21t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T3 20.25t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113z");
}

</style>
