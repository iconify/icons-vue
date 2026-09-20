<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gskjo6_7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:health-and-beauty-outline-sharp" /></template>
<style>
.gskjo6_7b {
  fill: currentColor;
  d: path("m5.654 21l-3.462-9.577l4.77-2.846V3h2v5.577l4.769 2.846L10.269 21zm10.385 0v-1h4v-2.77h-4v-1h4v-2.768h-4v-1h4v-2.77h-4v-1h4V5.923h-4v-1h5.769V21zM6.36 20h3.2l2.95-8.15l-3.677-2.196H7.088L3.412 11.85zm1.6-5.173");
}

</style>
