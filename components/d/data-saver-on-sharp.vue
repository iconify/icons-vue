<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4bpbcc_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-saver-on-sharp" /></template>
<style>
.t4bpbcc_c {
  fill: currentColor;
  d: path("M12 21q-1.868 0-3.51-.707T5.633 18.36t-1.924-2.864T3 12q0-3.425 2.244-5.98T11 3.05v1.23q-2.998.409-4.884 2.621Q4.231 9.114 4.231 12q0 3.219 2.275 5.494T12 19.769q1.889 0 3.534-.834q1.645-.835 2.658-2.189l1.062.654q-1.293 1.702-3.17 2.651T12 21m-.5-5.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zm8.766.05l-1.062-.615q.263-.581.414-1.344T19.77 12q0-2.944-1.924-5.147T13 4.281V3.05q3.377.317 5.689 2.902Q21 8.537 21 12q0 .985-.18 1.885t-.554 1.665");
}

</style>
