<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w49l9dwta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-chip-outline" /></template>
<style>
.w49l9dwta {
  fill: currentColor;
  d: path("M12 15.385q.1 0 .267-.181l.075-.112q.337-.679.925-1.167q.59-.488 1.01-1.104q.237-.348.355-.74t.118-.814q0-1.12-.803-1.886t-1.944-.765t-1.96.761t-.818 1.883q0 .423.121.818t.355.749q.426.604 1.01 1.094q.582.49.922 1.171l.075.107q.025.036.292.186m-.753-3.27q-.305-.307-.305-.752q0-.446.308-.75t.753-.305t.75.307t.305.753t-.308.75t-.753.305t-.75-.307M8 18q-2.507 0-4.253-1.745Q2 14.509 2 12.004t1.747-4.255T8 6h8q2.507 0 4.254 1.745T22 11.996t-1.747 4.255T16 18zm0-1h8q2.075 0 3.538-1.463T21 12t-1.463-3.537T16 7H8Q5.925 7 4.463 8.463T3 12t1.463 3.538T8 17m4-5");
}

</style>
