<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-1vicb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fencing-epee" /></template>
<style>
.f-1vicb7u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.647 13.413q1.034 1.343 1.07 3.11q.043 2.153-1.416 3.735q-.05.055-.109.098q-.06.044-.127.075t-.139.048t-.145.02t-.147-.008q-.073-.012-.143-.037t-.132-.064q-.063-.038-.117-.089q-.012-.01-.022-.021L7.5 17.561L3.53 21.53q-.105.106-.243.163T3 21.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.969-3.97l-2.719-2.72q-.106-.105-.163-.243T3.5 13.25t.057-.287t.163-.243q.01-.011.022-.021q1.582-1.459 3.735-1.416q1.767.036 3.11 1.07L20.47 2.47q.052-.053.113-.094t.13-.069t.141-.043T21 2.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T21.75 3t-.057.287t-.163.243z");
}

</style>
