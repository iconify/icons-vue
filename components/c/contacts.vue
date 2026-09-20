<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpve_rbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contacts" /></template>
<style>
.lpve_rbge {
  fill: currentColor;
  d: path("M4.5 21.385v-1h15v1zm0-17.77v-1h15v1zM12 14q1.039 0 1.77-.73t.73-1.77t-.73-1.77T12 9t-1.77.73t-.73 1.77t.73 1.77T12 14m-7.384 5q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm2.442-1h9.884q-1.125-1.016-2.36-1.508T12 16t-2.583.492T7.057 18");
}

</style>
