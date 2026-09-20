<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjmwi-6_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:air-purifier-sharp" /></template>
<style>
.gjmwi-6_r {
  fill: currentColor;
  d: path("M4 20V7q0-1.237.881-2.119T7 4h7q1.238 0 2.119.881T17 7v1h-1v9h1v3zm8.623-5.877q.877-.877.877-2.123t-.877-2.123T10.5 9t-2.123.877T7.5 12t.877 2.123T10.5 15t2.123-.877m-3.535-.71Q8.5 12.825 8.5 12t.588-1.412T10.5 10t1.413.588T12.5 12t-.587 1.413T10.5 14t-1.412-.587M16.5 11.5v-1h.4q.383 0 .681-.17t.48-.55q.298-.609.841-.944q.543-.336 1.198-.336h.4v1h-.4q-.383 0-.681.17t-.48.55q-.298.609-.841.944q-.543.336-1.198.336zm0 4v-1h.4q.383 0 .681-.17t.48-.55q.298-.57.841-.925T20.1 12.5h.4v1h-.4q-.383 0-.681.17t-.48.55q-.298.609-.841.944q-.543.336-1.198.336z");
}

</style>
