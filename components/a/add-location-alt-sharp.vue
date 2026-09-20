<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_c47_b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-location-alt-sharp" /></template>
<style>
.o_c47_b1b {
  fill: currentColor;
  d: path("M13.143 11.255q.473-.475.473-1.143t-.476-1.14t-1.143-.472t-1.14.476t-.472 1.143t.475 1.14t1.144.472t1.14-.476M12 21.02q-3.525-3.117-5.31-5.814q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3q.327 0 .625.024t.606.092v3.653h3v3h2.848q.011.121.014.258t.003.27q0 2.21-1.785 4.908q-1.786 2.697-5.311 5.814M18 8V5h-3V4h3V1h1v3h3v1h-3v3z");
}

</style>
