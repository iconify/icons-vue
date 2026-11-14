<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7rg45bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-axe" /></template>
<style>
.s7rg45bvh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.106 4.59q-1.217-.657-2.195.321t-.321 2.195l1.485 2.758L2.47 20.47q-.053.052-.094.113t-.069.13t-.043.141T2.25 21t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T3 21.75t.287-.057t.243-.163l10.142-10.142l.367 1.099q.39 1.172 1.592 1.456q1.203.284 2.076-.59l2.646-2.646q.874-.873.59-2.076q-.284-1.202-1.456-1.593l-2.128-.709q-.061-.02-.117-.05z");
}

</style>
