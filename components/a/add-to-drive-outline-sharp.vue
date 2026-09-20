<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsjgbebzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-to-drive-outline-sharp" /></template>
<style>
.dsjgbebzk {
  fill: currentColor;
  d: path("M7.044 19h5.445l-3.797-6.5H5.963l-1.382 2.352q-.389.645-.376 1.388t.376 1.385t1.03 1.009T7.044 19M12 16.173l2.162-3.673H9.839zM6.537 11.5h8.198l1.342-2.289l-1.658-2.807q-.388-.633-1.025-1.019T11.992 5t-1.416.376t-1.04 1.028zm6.398 8.5h-5.89q-1.053 0-1.94-.504q-.886-.504-1.409-1.383q-.523-.88-.523-1.885t.523-1.882l4.981-8.442q.523-.877 1.414-1.39Q10.981 4 12 4q1.027 0 1.904.514q.877.513 1.4 1.39l3.925 6.654q-.292-.054-.607-.075q-.314-.021-.606.02l-1.366-2.316l-2.75 4.707q-.57.781-.843 1.727q-.274.947-.274 2.025q0 .347.04.694q.041.347.111.66M18 22v-3h-3v-1h3v-3h1v3h3v1h-3v3zm-1.35-11.814");
}

</style>
