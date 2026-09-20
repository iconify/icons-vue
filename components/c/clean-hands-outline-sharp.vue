<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjdzfby0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clean-hands-outline-sharp" /></template>
<style>
.fjdzfby0n {
  fill: currentColor;
  d: path("m14.02 21.923l-7.616-2.22V21h-4v-8.154h6.373l7.358 2.693v1.615H21v2.615zM3.403 20h2v-6.154h-2zm10.565.862l6.008-1.831v-.877h-6.921L9.95 17.142l.33-.957l2.926.969h1.929v-.92l-6.516-2.388H6.404v4.808zm.897-8.193l-1-.346v-.885q-.012-1.45-1.028-2.463t-2.472-1.013q-1.287 0-2.176.749t-1.194 1.866H5.962q.29-1.371 1.278-2.373q.987-1.002 2.626-1.22V4h-1.5V3h5q.6 0 1.157.16q.558.16 1.029.442l-.733.733q-.33-.162-.69-.248Q13.772 4 13.367 4h-2.5v2.985q1.84.234 2.92 1.539t1.08 2.938zm2.568-3.487Q17 8.748 17 8.116q0-.48.339-1.195Q17.677 6.206 18.5 5q.823 1.206 1.162 1.912T20 8.116q0 .632-.434 1.066q-.433.434-1.066.434t-1.066-.434");
}

</style>
