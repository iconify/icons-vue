<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oetygccpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:forecast-model" /></template>
<style>
.oetygccpo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.961 13.218q1.322 1.146 3.065 1.032h8.749q1.864-.063 3.137-1.425T19.123 9.6T17.7 6.463q-1.192-1.115-2.768-1.207q-1.745-2.774-5.131-2.585q-3.385.188-4.812 3.136q-1.455.249-2.457 1.404q-1.155 1.333-1.029 3.092t1.458 2.915M20 15h-2q-2.5 0-2.5 2.5v2.25q0 2.5 2.5 2.5h2q1.036 0 1.768-.732t.732-1.768V17.5q0-2.5-2.5-2.5m-2 1.5h.25V18H17v-.5q0-1 1-1m1.75 0H20q1 0 1 1v.5h-1.25zm-2.75 3h1.25v1.25H18q-.414 0-.707-.293T17 19.75zm2.75 0H21v.25q0 1-1 1h-.25z");
}

</style>
