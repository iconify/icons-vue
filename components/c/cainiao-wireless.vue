<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nl1duobto"/><path class="anbft5b6q"/><path class="mxmeyr1vb"/><path class="mj_9160fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cainiao-wireless" /></template>
<style>
.anbft5b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.427 20.045a3.712 3.712 0 0 1 7.425 0");
}

.mj_9160fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.92 28.332l3.622-2.994l3.013 2.766");
}

.mxmeyr1vb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.947 9.532c-4.456-.048-7.868 3.512-8.181 6.558a25 25 0 0 0 .144 4.976c2.096 11.891 25.204 7.67 25.287.068c.014-1.331-.115-2.692-.203-4.021c-.321-4.862-4.934-7.452-7.748-7.482Zm7.927 28.123v4.33h2.975l-2.975-1.972m-6.35-2.026v4.066h-3.538l3.538-2.147");
}

.nl1duobto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.766 34.278c8.406 6.91 21.747 2.805 25.016-.203c7.425-.95 5.895-9.82 3.11-12.44c-1.323-4.9-2.245-11.759-7.933-13.32c-4.535-4.025-9.479-4.075-15.145-.203c-5.429 1.977-7.159 7.48-8.429 13.793c-3.954 4.48-3.75 10.104 3.38 12.373Z");
}

</style>
