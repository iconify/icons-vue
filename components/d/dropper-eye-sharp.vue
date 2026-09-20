<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shm5u_b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dropper-eye-sharp" /></template>
<style>
.shm5u_b3a {
  fill: currentColor;
  d: path("M4 20v-3.366l8.771-8.77l-1.81-1.791l.714-.707l2.329 2.303l3.935-3.953l2.327 2.365l-3.954 3.954l1.823 1.854l-.708.707l-3.942-4.019L5 17.017V19h1.742q.154.28.317.521q.162.24.333.479zm11.135 2q-1.833 0-3.383-.94t-2.483-2.521q.933-1.581 2.483-2.522t3.382-.94t3.383.94T21 18.538q-.933 1.581-2.483 2.521q-1.55.941-3.382.941m1.256-2.206q.513-.513.513-1.256t-.513-1.255t-1.256-.514t-1.256.514t-.513 1.255t.513 1.256t1.256.514t1.256-.514m-1.963-.549q-.293-.293-.293-.707t.293-.706q.293-.294.707-.294q.413 0 .706.294t.294.706t-.294.707t-.706.293t-.707-.293");
}

</style>
