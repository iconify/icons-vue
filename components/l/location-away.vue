<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-ipxbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-away" /></template>
<style>
.k8-ipxbel {
  fill: currentColor;
  d: path("M10.5 20v-1.323q0-.371.205-.68q.205-.308.52-.507q1.092-.655 2.297-.976q1.205-.322 2.478-.322t2.478.322t2.297.977q.316.198.52.506q.205.309.205.68V20zM3 20V9.5l7-5.288l3.99 3.011q-1.298.552-2.086 1.743t-.788 2.63q0 .814.24 1.55q.242.735.7 1.335q-.539.2-1.05.432t-.998.525q-.881.525-1.387 1.396q-.505.87-.505 1.843V20zm11.23-6.634q-.73-.731-.73-1.77q0-1.038.73-1.769t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73");
}

</style>
