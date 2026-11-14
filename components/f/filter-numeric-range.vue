<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2qqj3jxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-numeric-range" /></template>
<style>
.o2qqj3jxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.492 18.335q-.077.062-.162.114q-.086.051-.177.089q-.092.039-.188.064t-.195.035t-.198.008t-.197-.021q-.098-.017-.192-.048q-.094-.032-.183-.076l-1.033-.516q-.108-.054-.208-.123t-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237Q8 16.539 8 16.418v-4.845q0-.279-.087-.545q-.087-.265-.252-.49L4.542 6.285q-.071-.097-.129-.204q-.057-.106-.099-.219t-.069-.231q-.026-.117-.036-.238t-.003-.241t.03-.239t.062-.232t.094-.222t.123-.207q.069-.099.151-.188q.082-.088.175-.165t.196-.14t.213-.112t.227-.081q.116-.033.236-.049q.119-.017.24-.017h8.094q.121 0 .24.017q.12.016.236.049t.227.081t.213.112t.196.14t.175.165t.151.188t.123.207t.094.222t.062.232t.03.239t-.003.241t-.036.238t-.069.231q-.042.113-.099.219q-.058.107-.129.204l-3.119 4.253q-.165.225-.252.49q-.087.266-.087.545v4.579m3.75.598h4.5a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-.75a1.5 1.5 0 0 1 1.5-1.5m.5 0v1.5m1.75-1.5v2m1.75-2v1.5");
}

</style>
