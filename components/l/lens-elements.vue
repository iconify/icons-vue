<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsgbw_bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lens-elements" /></template>
<style>
.gsgbw_bxn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.75h12q1.76 0 3.005 1.245T22.25 8v8q0 1.76-1.245 3.005T18 20.25H6q-1.76 0-3.005-1.245T1.75 16V8q0-1.76 1.245-3.005T6 3.75m10.592 3.29q-.058-.074-.132-.132q-.117-.092-.261-.131t-.292-.021t-.278.092t-.221.192q-3.858 4.96 0 9.92q.058.074.132.132q.058.045.124.078q.066.034.137.053q.071.02.145.025t.147-.004t.143-.032q.071-.024.135-.06q.064-.037.12-.085t.101-.107q3.858-4.96 0-9.92m-8 9.92q3.858-4.96 0-9.92q-.058-.074-.132-.132q-.058-.045-.124-.078q-.066-.034-.137-.053q-.071-.02-.145-.025t-.147.004t-.143.032q-.071.024-.135.06q-.064.037-.12.085t-.101.107q-3.858 4.96 0 9.92q.058.074.132.132q.058.045.124.078q.066.034.137.053q.071.02.145.025t.147-.004t.143-.032q.071-.024.135-.06q.064-.037.12-.085t.101-.107");
}

</style>
