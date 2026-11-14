<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkkfqhbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:latkes" /></template>
<style>
.bkkfqhbyj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.827 8.25h4.346q-.247-1.172-1.287-2.124q-.509-.466-.886-.893q-.377.427-.886.893q-1.04.952-1.287 2.124m5.871 0h1.927q1.087 0 1.856.769t.769 1.856q0 .687-.307 1.248q.576.184 1.038.646q.769.769.769 1.856t-.769 1.856q-.167.167-.348.297q.367.615.367 1.597Q21 21 18.375 21H5.625Q3 21 3 18.375q0-.795.411-1.42q-1.161-.584-1.161-2.33q0-2.107 1.692-2.523q-.192-.518-.192-1.227q0-2.625 2.625-2.625h1.927q.258-1.82 1.799-3.231q.882-.807 1.263-1.416q.039-.063.09-.117t.111-.097t.127-.073t.139-.047q.072-.016.146-.019t.147.01t.142.039t.131.065q.147.092.239.239q.381.609 1.263 1.416Q15.44 6.43 15.698 8.25");
}

</style>
