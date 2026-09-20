<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2xj0_bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:accessible-forward-sharp" /></template>
<style>
.o2xj0_bzq {
  fill: currentColor;
  d: path("M8.192 21q-1.748 0-2.97-1.251T4 16.75t1.241-2.99q1.242-1.24 2.97-1.24v1.019q-1.326 0-2.269.942T5 16.75t.942 2.27t2.289.942t2.288-.943t.943-2.269h1q0 1.748-1.261 2.999T8.192 21m8.347-1v-4.173H9.322l-.732-1.13l2.736-6.024H8.802l-.696 1.839l-.944-.32l.982-2.673h4.825q.875 0 1.328.644q.453.643.06 1.514l-2.207 4.785h5.389V20zM13.635 6.345q-.462-.462-.462-1.133t.463-1.134t1.133-.463t1.124.463q.453.462.453 1.133q0 .672-.453 1.134q-.452.463-1.124.463t-1.133-.463");
}

</style>
