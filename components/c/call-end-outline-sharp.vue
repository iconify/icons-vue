<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1zlyv41s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-end-outline-sharp" /></template>
<style>
.p1zlyv41s {
  fill: currentColor;
  d: path("m4.064 16.366l-2.972-2.91l.635-.66q2.106-2.179 4.841-3.237T12 8.5t5.407 1.071t4.847 3.225l.654.66l-2.971 2.91l-3.437-2.597v-3.465q-1.142-.396-2.277-.6T12 9.5t-2.223.204t-2.277.6v3.465zM6.5 10.68q-1.129.529-2.17 1.237T2.509 13.4l1.654 1.654L6.5 13.269zm11 .011v2.539l2.339 1.823l1.692-1.604q-.917-.842-1.9-1.529T17.5 10.692m0 0");
}

</style>
