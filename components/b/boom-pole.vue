<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahlatwbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boom-pole" /></template>
<style>
.ahlatwbov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.608 3.392q.879.878.879 2.121t-.879 2.121l-2.474 2.474q-.878.879-2.121.879q-.849 0-1.529-.411L7.531 17.53H7.53v.001l-3.5 3.499q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113L5.939 17L3.97 15.03q-.106-.105-.163-.243T3.75 14.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094L7 15.939l6.424-6.423q-.411-.68-.411-1.529q0-1.243.879-2.121l2.474-2.474q.878-.879 2.121-.879t2.121.879");
}

</style>
