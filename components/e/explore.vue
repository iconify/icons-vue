<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppx_vqbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:explore" /></template>
<style>
.ppx_vqbwe {
  fill: currentColor;
  d: path("m7.5 16.5l7-2l2-7l-7 2zm4.5-3q-.625 0-1.062-.437T10.5 12t.438-1.062T12 10.5t1.063.438T13.5 12t-.437 1.063T12 13.5m0 8.5q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
