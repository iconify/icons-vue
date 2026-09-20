<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2ew-db9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:encrypted-minus-circle-rounded" /></template>
<style>
.n2ew-db9l {
  fill: currentColor;
  d: path("M14.885 17.385h4.23q.162 0 .274-.112T19.5 17t-.111-.273t-.273-.111h-4.231q-.162 0-.273.111T14.5 17t.112.273t.272.112M17 21q-1.671 0-2.835-1.164Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21M5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923v3.57q0 .348-.279.572t-.646.157q-.258-.068-.534-.092Q17.264 11 17 11q-2.496 0-4.248 1.752T11 17q0 .627.14 1.274q.139.647.45 1.326q.187.398-.108.716t-.693.15q-1.147-.512-2.08-1.293q-.932-.78-1.703-1.865q-.94-1.322-1.473-2.901T5 11.1m7-2.58q-.613 0-1.037.433q-.424.434-.424 1.047t.424 1.038t1.037.424q.217 0 .406-.068t.348-.221q.092-.086.19-.158t.214-.13q.17-.194.247-.411T13.48 10q0-.613-.434-1.047q-.433-.434-1.047-.434");
}

</style>
