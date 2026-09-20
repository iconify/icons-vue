<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzmqvd_zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:key-outline-sharp" /></template>
<style>
.gzmqvd_zs {
  fill: currentColor;
  d: path("M5.588 13.413Q5 12.825 5 12t.588-1.412T7 10t1.413.588T9 12t-.587 1.413T7 14t-1.412-.587M7 18q-2.5 0-4.25-1.75T1 12t1.75-4.25T7 6q1.675 0 3.038.825T12.2 9H21l3 3l-4.5 4.5l-2-1.5l-2 1.5l-2.125-1.5H12.2q-.8 1.35-2.162 2.175T7 18m0-2q1.4 0 2.463-.85T10.875 13H14l1.45 1.025L17.5 12.5l1.775 1.375L21.15 12l-1-1h-9.275q-.35-1.3-1.412-2.15T7 8Q5.35 8 4.175 9.175T3 12t1.175 2.825T7 16");
}

</style>
