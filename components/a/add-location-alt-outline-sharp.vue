<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa4k_nbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-location-alt-outline-sharp" /></template>
<style>
.xa4k_nbmw {
  fill: currentColor;
  d: path("M12 21.02q-3.525-3.118-5.31-5.815q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3h.308q.154 0 .308.012v1.005q-.154-.011-.3-.024q-.147-.012-.316-.012q-2.621 0-4.359 1.785q-1.737 1.786-1.737 4.53q0 1.852 1.638 4.39T12 19.677q2.78-2.415 4.41-4.905q1.629-2.49 1.686-4.341v-.046h1v.046q-.057 2.192-1.833 4.85T12 21.02m1.143-9.764q.472-.475.472-1.143t-.475-1.14t-1.143-.472t-1.14.476t-.472 1.143t.475 1.14t1.144.472t1.14-.476M18 8h1V5h3V4h-3V1h-1v3h-3v1h3z");
}

</style>
