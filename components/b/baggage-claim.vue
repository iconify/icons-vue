<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ad252xc8e"/><g class="n1mjunbsu"><path class="x4d-q402f"/><path class="n0-qmeb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:baggage-claim" /></template>
<style>
.ad252xc8e {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.956 57.06a6.894 6.894 0 0 1-6.895 6.898H6.891A6.895 6.895 0 0 1 0 57.06V6.9A6.893 6.893 0 0 1 6.891.006h50.17A6.894 6.894 0 0 1 63.956 6.9z");
}

.n0-qmeb2z {
  d: path("M32.02 8.185c-5.412 0-9.796 5.51-9.796 12.3c0 6.789 4.385 12.294 9.796 12.294c5.408 0 9.795-5.506 9.795-12.294c0-6.79-4.386-12.3-9.795-12.3m0 22.482c-4.481 0-8.112-4.558-8.112-10.182s3.631-10.184 8.112-10.184c4.478 0 8.111 4.56 8.111 10.184s-3.633 10.182-8.111 10.182");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.x4d-q402f {
  d: path("M54.13 45.11c0 1.83-1.165 3.311-2.608 3.311H12.534c-1.446 0-2.616-1.48-2.616-3.311V17.795c0-1.827 1.17-3.309 2.616-3.309h38.988c1.443 0 2.608 1.481 2.608 3.309zm-5.242 6.519c2.896 0 5.24.324 5.24.724v2.75c0 .397-2.345.724-5.24.724H15.153c-2.89 0-5.239-.326-5.239-.724v-2.75c0-.399 2.349-.724 5.239-.724z");
}

</style>
