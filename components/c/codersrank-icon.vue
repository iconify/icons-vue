<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":164};
const content = `<path class="bv-25ybft"/><path class="vg6lr0neq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codersrank-icon" /></template>
<style>
.bv-25ybft {
  fill: var(--svg-color--19223c, #19223c);
  d: path("M139.54.23L9.01 82.4C2.863 86.117-.142 90.28.005 94.892v12.506q.22 6.923 9.233 12.28l64.599 37.286a3.047 3.047 0 0 0 4.393-1.565l14.504-35.05l-30.761-17.417a5.5 5.5 0 0 1-2.157-2.001a5.645 5.645 0 0 1 .278-6.332a5.7 5.7 0 0 1 1.656-1.49l56.474-34.61l23.287-56.705a1.36 1.36 0 0 0-.432-1.511a1.3 1.3 0 0 0-.765-.284a1.3 1.3 0 0 0-.783.23z");
}

.vg6lr0neq {
  fill: var(--svg-color--67a4ac, #67a4ac);
  d: path("M246.763 46.002L183.05 7.376a3.046 3.046 0 0 0-4.394 1.343l-14.94 35.05l30.32 18.088a5.5 5.5 0 0 1 2.107 2.048a5.65 5.65 0 0 1 0 5.72a5.5 5.5 0 0 1-2.106 2.056l-56.911 33.49l-24.173 56.264a1.357 1.357 0 0 0 .11 1.897a1.31 1.31 0 0 0 1.457.206a1.3 1.3 0 0 0 .41-.316l41.752-25.23l16.48 23.67a3.97 3.97 0 0 0 3.295 1.783h39.553a3.91 3.91 0 0 0 3.492-2.124a4.07 4.07 0 0 0-.197-4.13l-26.809-41.084l54.276-32.818Q256 77.706 256 70.783v-12.28c0-4.616-3.076-8.779-9.233-12.501z");
}

</style>
