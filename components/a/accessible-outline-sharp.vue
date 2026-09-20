<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ju6du_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:accessible-outline-sharp" /></template>
<style>
.b-ju6du_e {
  fill: currentColor;
  d: path("M10.905 5.768q-.501-.5-.501-1.191q0-.69.5-1.191t1.192-.502t1.191.502t.501 1.191q0 .69-.5 1.191t-1.192.501t-1.191-.5m6.422 15.77V16.5h-6.73V9q0-.633.433-1.066q.434-.434 1.066-.434q.35 0 .701.195t.832.751q1.394 1.631 2.42 2.234t2.393.781v1q-1.46-.153-2.626-.796q-1.168-.642-2.374-1.923v5.412h4.885v6.384zm-7.23 0q-1.864 0-3.202-1.338T5.558 17q0-1.742 1.137-3.002t2.901-1.494v1.012q-1.298.195-2.168 1.16T6.558 17q0 1.48 1.029 2.51q1.029 1.028 2.51 1.028q1.359 0 2.323-.87q.965-.87 1.16-2.168h1.012q-.196 1.725-1.475 2.882q-1.278 1.156-3.02 1.156");
}

</style>
