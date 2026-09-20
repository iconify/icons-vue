<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l02jcl-8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hide-source-rounded" /></template>
<style>
.l02jcl-8e {
  fill: currentColor;
  d: path("m19.479 20.9l-1.883-1.877q-1.167.935-2.583 1.456T12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12q0-1.596.521-3.012q.521-1.417 1.456-2.584L3.094 4.52q-.146-.146-.155-.347t.155-.366t.357-.166t.357.166l16.384 16.384q.146.147.156.345t-.156.363t-.357.166q-.19 0-.356-.166m-.823-5.056l-10.5-10.5q-.373-.373-.286-.883q.088-.509.547-.727q.835-.367 1.732-.55T12 3q1.864 0 3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12q0 .954-.184 1.851q-.183.897-.55 1.732q-.218.46-.725.55t-.885-.289");
}

</style>
