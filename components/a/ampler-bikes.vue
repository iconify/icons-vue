<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zbk81rn_c"/><path class="t8e721lwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ampler-bikes" /></template>
<style>
.t8e721lwp {
  d: path("M10.576 23.074V16.45l5.497-3.174l.024 9.707m-5.521-3.4h5.513m4.018 3.471V11.077l3.839-2.217l4.074 2.352v11.842M23.946 8.86v8.003m7.915 6.191v-9.506l5.618 3.244v2.702h-5.58M10.472 26.48v4.816l5.88 3.395m10.874-8.211H20.08l-.037 10.228l3.922 2.265l3.26-1.827m-7.178-5.18h5.647m5.303 3.439V26.48h6.436v2.263l-2.99 1.739l2.664 1.566");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zbk81rn_c {
  d: path("M6.192 13.622L23.926 3.383l17.898 10.334v20.461L24.15 44.383L6.329 34.095z");
}

</style>
