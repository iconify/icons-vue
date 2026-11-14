<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vslydjb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:devops" /></template>
<style>
.vslydjb2g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.03 5.47l1.646 1.646q1.703-.017 2.809 1.129Q21.75 9.556 21.75 12t-1.265 3.755q-1.197 1.241-3.096 1.118q-3.339-.215-5.389-3.361q-2.024 3.107-5.307 3.356L5.03 18.53q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.75 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l.842-.843q-.728-.282-1.297-.872Q2.25 14.444 2.25 12t1.265-3.755q1.197-1.241 3.096-1.118Q9.95 7.342 12 10.488q1.552-2.382 3.843-3.084l-.873-.874q-.053-.052-.094-.113t-.069-.13t-.043-.141T14.75 6t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094");
}

</style>
