<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzuw5xb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gift-aid" /></template>
<style>
.mzuw5xb_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.29 6.75Q6.75 6.042 6.75 5q0-2.25 2.25-2.25q1.5 0 2.662 1.55q.185.246.338.5q.153-.254.338-.5Q13.5 2.75 15 2.75q2.25 0 2.25 2.25q0 1.042-.54 1.75h2.54q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768q-.35.349-.768.532v.597Q19.655 13 19 13h-.25v-.25h-6v2.596Q12 16.518 12 18q0 2.071 1.464 3.536q.112.111.227.214H6q-2.25 0-2.25-2.25v-6.95q-.418-.183-.768-.532q-.732-.732-.732-1.768v-1q0-2.5 2.5-2.5zm-2.04 6h6v7.5H6q-.75 0-.75-.75zM17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
