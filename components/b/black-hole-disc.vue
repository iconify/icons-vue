<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzxvh_z7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:black-hole-disc" /></template>
<style>
.gzxvh_z7v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.818 7.318Q7.5 8.636 7.5 10.5t1.318 3.182T12 15t3.182-1.318T16.5 10.5t-1.318-3.182T12 6T8.818 7.318M3.251 12.87q.061-1.199 2.525-2.172q.138-.055.246-.159t.166-.241q.059-.136.062-.286q.002-.149-.052-.288q-.028-.068-.068-.13t-.091-.116t-.112-.095t-.129-.071t-.14-.045t-.146-.017t-.146.012q-.073.013-.142.04q-3.362 1.329-3.471 3.492q-.111 2.203 3.162 3.61Q7.851 17.667 12 17.667t7.085-1.263q3.273-1.407 3.162-3.61q-.109-2.163-3.471-3.492q-.139-.054-.288-.052q-.15.003-.286.062q-.137.059-.241.166t-.159.246q-.027.069-.04.142t-.012.146t.017.146t.045.14t.071.129t.095.112t.116.091t.13.068q2.464.973 2.525 2.172q.058 1.161-2.257 2.156Q15.84 16.167 12 16.167t-6.492-1.141q-2.315-.995-2.257-2.156");
}

</style>
