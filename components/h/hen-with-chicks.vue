<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvusjmz8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hen-with-chicks" /></template>
<style>
.wvusjmz8c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.495 4.504q.531.68.731 1.79l.772 1.933q3.202-.304 5.331-4.562q.067-.134.18-.232q.112-.097.254-.145q.141-.047.29-.036q.149.01.282.077q.071.036.134.085q4.373 3.499 2.227 8.865q-.022.055-.053.107Q18.625 15.75 11 15.75q-2.985 0-4.586-2q-1.437-1.797-1.215-4.562L3.165 8.171q-.134-.067-.232-.18q-.097-.112-.145-.254q-.047-.141-.036-.29q.01-.149.077-.282q.098-.196.285-.308L5.343 5.52q.219-.807.667-1.303q.072-.985.654-1.625q.662-.725 1.617-.685q2.117.088 2.214 2.597M8.031 3.43q.13 0 .266.009q.081.005.16.013q-.108-.041-.238-.046q-.099-.005-.188.024M2.5 19.75q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5m9.25-2.5q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5m4.25 2.5q0-2.5 2.5-2.5q1.036 0 1.768.732T21 19.75t-.732 1.768t-1.768.732q-2.5 0-2.5-2.5");
}

</style>
