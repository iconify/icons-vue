<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3i5obaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:call-centre-headset" /></template>
<style>
.ye3i5obaa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 11v.317q-1.75.341-1.75 2.433v2.5q0 1.036.732 1.768q.465.464 1.052.634Q4.67 22.25 9.5 22.25H12q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 20.75H9.5q-3.297 0-3.695-2.125q.533-.178.963-.607q.732-.732.732-1.768v-2.5q0-2.092-1.75-2.433V11q0-2.589 1.831-4.419Q9.411 4.75 12 4.75t4.419 1.831T18.25 11v.317q-1.75.341-1.75 2.433v2.5q0 1.036.732 1.768T19 18.75t1.768-.732t.732-1.768v-2.5q0-2.092-1.75-2.433V11q0-3.21-2.27-5.48T12 3.25T6.52 5.52T4.25 11");
}

</style>
