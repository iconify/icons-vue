<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfwk594rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lips" /></template>
<style>
.pfwk594rs {
  fill: currentColor;
  d: path("M11.35 19q-3.475 0-6.225-1.987T1.25 11.775Q3.9 12.8 6.638 13.4T12 14q2.8 0 5.45-.638t5.3-1.587q-1.125 3.25-3.875 5.238T12.65 19zm.675-7q-2.575 0-5.062-.612T2 10l4.05-4.05q.425-.425.988-.663t1.137-.237q.425 0 .863.138t.812.387L12 7l2.15-1.425q.375-.25.813-.387t.862-.138q.575 0 1.138.238t.987.662l3.975 3.975Q19.5 10.8 17.05 11.4t-5.025.6");
}

</style>
