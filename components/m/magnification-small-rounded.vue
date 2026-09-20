<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5wg-nbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:magnification-small-rounded" /></template>
<style>
.a5wg-nbdp {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm3.45-8.934Q8.5 9.633 8.5 9t-.434-1.066T7 7.5t-1.066.434Q5.5 8.367 5.5 9t.434 1.066T7 10.5t1.066-.434");
}

</style>
