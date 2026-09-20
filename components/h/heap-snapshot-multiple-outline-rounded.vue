<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4lgpvf1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heap-snapshot-multiple-outline-rounded" /></template>
<style>
.a4lgpvf1z {
  fill: currentColor;
  d: path("M11.782 10.282Q12 10.064 12 9.75t-.218-.532T11.25 9t-.532.218t-.218.532t.218.532t.532.218t.532-.218m.003 4.147l4.15-4.15q.146-.146.156-.347q.009-.201-.156-.366q-.166-.166-.357-.166t-.357.166l-4.155 4.155q-.147.146-.154.345q-.006.198.16.363q.164.165.356.165t.356-.165m4.498.353q.218-.219.218-.532t-.218-.532t-.532-.218t-.532.218t-.218.532t.218.532t.532.218t.532-.218M18.384 18H8.616q-.691 0-1.153-.462T7 16.384V3.616q0-.691.463-1.153T8.616 2h6.213q.323 0 .628.13t.522.349L19.52 6.02q.218.218.348.522t.131.628v9.214q0 .69-.462 1.153T18.384 18M19 7h-3.077q-.394 0-.659-.264Q15 6.47 15 6.077V3H8.616q-.231 0-.424.192T8 3.616v12.769q0 .23.192.423t.423.192h9.77q.23 0 .423-.192t.192-.424zM4.616 22q-.691 0-1.153-.462T3 20.385V8.5q0-.213.143-.357T3.5 8t.357.143T4 8.5v11.885q0 .23.192.423t.423.192H13.5q.214 0 .357.143T14 21.5t-.143.357T13.5 22zM8 3v4zv14z");
}

</style>
