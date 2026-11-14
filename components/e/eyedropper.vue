<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoz6g5ddb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eyedropper" /></template>
<style>
.uoz6g5ddb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.248 4.752q.806.805.806 1.944q0 1.14-.806 1.945l-1.768 1.768q-.484.485-1.089.678l1.089 1.09q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-1.292-1.291q-.185.292-.477.584l-4.378 4.378q-.326.327-.755.499l-1.483.592q-.958.382-1.687-.347T6 15.966l.593-1.483q.172-.43.499-.757l4.378-4.377q.292-.292.584-.477L10.763 7.58q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163l1.09 1.089q.193-.605.678-1.089l1.768-1.768q.805-.806 1.944-.806q1.14 0 1.945.806");
}

</style>
