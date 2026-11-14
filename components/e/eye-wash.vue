<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js9s1l2_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-wash" /></template>
<style>
.js9s1l2_t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.688q-6.663 0-9.134 3.912q-.057.089-.086.192q-.03.102-.03.208t.03.208t.086.192Q5.337 13.313 12 13.313T21.134 9.4q.057-.089.086-.192q.03-.102.03-.208t-.03-.208q-.029-.103-.086-.192Q18.663 4.688 12 4.688m0 1.562q2.75 0 2.75 2.75T12 11.75T9.25 9T12 6.25m0 4q-1.25 0-1.25-1.25T12 7.75T13.25 9T12 10.25m-4.96 4.158q-.074.058-.132.132Q5 16.993 5 18.75q0 2.5 2.5 2.5q1.036 0 1.768-.732T10 18.75q0-1.757-1.908-4.21q-.045-.059-.101-.107t-.12-.085t-.135-.06t-.143-.032t-.147-.004t-.145.025t-.137.053t-.124.078m8.868.132q.058-.074.132-.132q.058-.045.124-.078q.066-.034.137-.053q.071-.02.145-.025t.147.004t.143.032t.135.06t.12.085t.101.107Q19 16.993 19 18.75q0 2.5-2.5 2.5t-2.5-2.5q0-1.757 1.908-4.21");
}

</style>
