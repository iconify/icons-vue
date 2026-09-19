<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fttr_ko7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edifier-connect" /></template>
<style>
.fttr_ko7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.91 26.94L21.206 6.99c1.93-4.506 8.366-2.575 5.792 3.217L15.415 32.733c-3.862 8.366-7.08 0-4.505-5.793m21.238-4.827l-9.01 17.699c-3.862 7.08-8.367 2.574-6.436-1.93l9.654-18.665c1.287-2.574 7.079-1.287 5.792 2.896M26.356 41.1l3.861-7.08c1.159-2.15 2.317-4.287 3.862-4.505s3.475 1.506 3.861 3.218s-.772 3.436-1.93 5.148c-1.288 1.931-2.575 2.574-2.575 2.574c-2.574 1.931-9.01 3.862-7.08.644");
}

</style>
