<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip5q5kb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:identity-platform-sharp" /></template>
<style>
.ip5q5kb1u {
  fill: currentColor;
  d: path("m12 20.175l5.12-3.136q-1.154-.741-2.455-1.14T12 15.5t-2.668.409q-1.303.408-2.482 1.124zm2.129-8.546Q15 10.758 15 9.5t-.871-2.129T12 6.5t-2.129.871T9 9.5t.871 2.129T12 12.5t2.129-.871M12 21.327l-8-4.885V7.558l8-4.885l8 4.885v8.884z");
}

</style>
