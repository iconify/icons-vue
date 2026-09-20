<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shw_geaam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-beaker-24-regular" /></template>
<style>
.shw_geaam {
  fill: currentColor;
  d: path("M12 5.5a4.5 4.5 0 0 0-4.495 4.285a.75.75 0 0 1-.75.715H6.5a3 3 0 1 0 0 6h8.407L14.05 18H6.5a4.5 4.5 0 0 1-.42-8.98A6.001 6.001 0 0 1 18 10h-1.463a.8.8 0 0 1-.042-.215A4.5 4.5 0 0 0 12 5.5m4.5 7h-.75a.75.75 0 0 1 0-1.5h5.5a.75.75 0 0 1 0 1.5h-.75v2.697a2 2 0 0 0 .263.992l.463.811h-5.453l.464-.814c.172-.302.263-.643.263-.991zm-2.3 7.257L15.201 18h6.595l1.002 1.757A1.5 1.5 0 0 1 21.497 22h-5.995a1.5 1.5 0 0 1-1.303-2.243");
}

</style>
