<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji0t45bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-kit" /></template>
<style>
.ji0t45bli {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 12.75q-1.76 0-3.005-1.245T7.75 8.5q0-1.858 1.963-5.257q.42-.727.631-1.107q.073-.131.19-.223q.117-.093.26-.134t.292-.024q.148.017.278.089q.159.089.26.24q.254.381.758 1.104q.798 1.146 1.274 1.965q.444-.646.616-1.335q.037-.145.125-.264q.089-.12.217-.197t.276-.099t.292.014q.092.023.175.068t.153.11t.12.144q.052.079.082.169q.538 1.615.538 4.737q0 1.76-1.245 3.005T12 12.75M12 14q-7.748 0-7.75 2.748v2.502q0 3.25 7.75 3.25t7.75-3.25v-2.5Q19.75 14 12 14m-6.25 5.25v-.613q1.91.863 6.25.863t6.25-.863v.613Q18.25 21 12 21t-6.25-1.75");
}

</style>
