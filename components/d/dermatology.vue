<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2pk2zjnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dermatology" /></template>
<style>
.q2pk2zjnb {
  fill: currentColor;
  d: path("M3 20v-7.38q0-.676.475-1.148Q3.949 11 4.615 11H9.5v1q0 1.042.729 1.77q.728.73 1.769.73t1.771-.73T14.5 12v-1h4.885q.666 0 1.14.475t.475 1.14V20zm9-7.5q-.213 0-.357-.144T11.5 12q0-2.601.596-5.13t2.562-4.235q.17-.121.369-.113q.198.009.339.17q.14.162.121.37t-.189.329q-1.827 1.551-2.313 3.878Q12.5 9.595 12.5 12q0 .213-.144.356t-.357.144m-5.77 2.734q.194-.19.194-.48t-.19-.484t-.48-.193t-.483.19t-.193.48t.19.483t.48.193t.483-.19m1 2.5q.193-.19.193-.48t-.19-.483t-.48-.193t-.483.19t-.193.48t.19.483t.48.193t.483-.19m11.5-2.5q.193-.19.193-.48t-.19-.483t-.48-.193t-.483.19t-.193.48t.19.483t.48.193t.483-.19");
}

</style>
