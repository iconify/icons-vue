<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0_k-xbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:creator-payout" /></template>
<style>
.z0_k-xbja {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.25H6.875q-2.123 0-3.624 1.501T1.75 7.375v5.25q0 2.123 1.501 3.624t3.624 1.501h5.13q.084-1.91 1.459-3.286Q14.929 13 17 13h2q1.748 0 3.064 1.043q.186-.67.186-1.418v-5.25q0-2.123-1.501-3.624T17.125 2.25M8.75 8.684q.001-1.32 1.153-1.964t2.276.048l2.138 1.316q1.07.66 1.07 1.916t-1.07 1.916l-2.138 1.316q-1.124.691-2.276.048q-1.152-.644-1.153-1.964zM17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906m-4.125-.25q.436 0 .846-.063Q17.829 17 17 17q-.866 0-.982.75z");
}

</style>
