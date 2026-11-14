<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr2-3_3yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:decor-bowl" /></template>
<style>
.lr2-3_3yu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 6.25h-19q-.149 0-.287.057t-.243.163t-.163.243T1.75 7q0 3.088 3.109 5.215q1.674 1.146 3.727 1.646l-.816 3.467q-.017.072-.02.146t.01.147t.038.142t.064.132t.09.117t.11.097q.06.043.127.074q.067.03.139.047q.085.02.172.02h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.087-.02-.172l-.816-3.467q2.053-.5 3.727-1.646Q22.25 10.088 22.25 7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M9.447 16.75l.616-2.618q.934.118 1.937.118t1.937-.118l.616 2.618z");
}

</style>
