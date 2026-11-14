<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc4no73sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baseball-bat" /></template>
<style>
.oc4no73sl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.045 16.42q-.383.382-.566.848l-.495-.495q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113L4 19.909q.022.024.045.046q.022.023.046.045l2.076 2.076q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-.495-.495q.466-.183.848-.566l3.927-3.926q.099-.1.213-.183l8.169-6.027q1.247-.92 1.363-2.464t-.98-2.639l-.988-.988q-1.095-1.096-2.639-.98t-2.464 1.363L8.154 12.28q-.083.114-.182.213z");
}

</style>
