<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szhgk2bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:feature-search" /></template>
<style>
.szhgk2bry {
  fill: currentColor;
  d: path("m18.454 8.746l3.315 3.316l-.707.707l-3.316-3.315q-.448.396-1.038.587t-1.208.19q-1.567 0-2.649-1.082T11.769 6.5t1.082-2.649T15.5 2.769t2.649 1.082T19.231 6.5q0 .675-.21 1.237q-.21.561-.567 1.01m-1.015-.309q.792-.792.792-1.938t-.792-1.939T15.5 3.77t-1.939.793T12.77 6.5t.792 1.939t1.939.792t1.939-.792M4.616 21q-.691 0-1.153-.462T3 19.385V6.615q0-.69.463-1.152T4.615 5H10q-.14.356-.173.807q-.033.45-.033.812q0 2.379 1.656 3.983t4.075 1.604q.436 0 .883-.063q.446-.062.907-.193L19 13.52v5.865q0 .69-.462 1.152T17.384 21z");
}

</style>
