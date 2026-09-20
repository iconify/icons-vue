<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp8gf_bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lips-sharp" /></template>
<style>
.rp8gf_bpi {
  fill: currentColor;
  d: path("M11.677 18q-3.321 0-5.783-1.766q-2.461-1.767-3.721-4.709q2.38.91 4.84 1.462t4.949.551q2.569 0 5.007-.58q2.439-.58 4.858-1.452q-1.125 2.942-3.702 4.718T12.342 18zm.29-5.462q-2.46 0-4.832-.574t-4.731-1.31L6.723 6.7q.348-.31.767-.48t.877-.17q.33 0 .651.09q.322.089.62.262l2.381 1.464L14.4 6.402q.298-.173.61-.262q.313-.09.642-.09q.46 0 .888.17q.427.17.776.48l4.244 3.937q-2.368.76-4.74 1.33q-2.374.572-4.853.572");
}

</style>
