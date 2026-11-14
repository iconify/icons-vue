<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyefprnnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-user" /></template>
<style>
.uyefprnnj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.701 8.89l4.5-3.937q2.799-2.45 5.598 0l4.5 3.937q1.451 1.27 1.451 3.198V16.5q0 1.76-1.245 3.005T16.5 20.75h-9q-1.76 0-3.005-1.245T3.25 16.5v-4.412q0-1.928 1.451-3.198M12 9q-2.25 0-2.25 2.25T12 13.5t2.25-2.25T12 9m0 5.75q-3.219 0-3.74 3.127q-.024.147.009.292q.034.146.121.267q.086.121.213.2t.274.104q.073.012.146.01q.074-.003.146-.019q.072-.017.139-.047q.068-.031.128-.074t.111-.096q.05-.054.089-.117t.066-.132q.026-.069.038-.142q.312-1.873 2.26-1.873t2.26 1.873q.012.073.038.142q.027.069.066.132t.089.117q.051.053.111.096t.128.074q.067.03.139.047q.072.016.146.019q.073.002.146-.01q.147-.025.274-.104t.213-.2q.087-.121.121-.267q.033-.145.009-.292q-.521-3.127-3.74-3.127");
}

</style>
