<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccoocea3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-lock" /></template>
<style>
.ccoocea3d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.75q-5.307 0-7.931 5.686q-.069.149-.069.314t.069.314Q4.443 15.75 9.75 15.75t7.931-5.686q.069-.149.069-.314t-.069-.314Q15.057 3.75 9.75 3.75m0 2.75Q13 6.5 13 9.75T9.75 13T6.5 9.75T9.75 6.5m0 5Q8 11.5 8 9.75T9.75 8t1.75 1.75t-1.75 1.75M17 16.25h2V16q0-.414-.293-.707T18 15q-1 0-1 1zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-1q0-1.768 1.25-2.286V16q0-2.5 2.5-2.5q1.036 0 1.768.732T20.5 16z");
}

</style>
