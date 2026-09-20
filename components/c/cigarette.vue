<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="auuykybgb"/><path class="mlvs6e_ws"/><path class="u8sibbwvn"/><path class="sc-opdb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cigarette" /></template>
<style>
.auuykybgb {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M13 30H2s-2 0-2-2v-5c0-2 2-2 2-2h11z");
}

.mlvs6e_ws {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M12 21h14v9H12z");
}

.sc-opdb0c {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M27.79 20a1 1 0 0 1-.988-.855c-.029-.2-.654-4.924 4.475-8.002c2.498-1.499 3.063-4.246 2.532-6.164C33.561 4.083 32.673 2 29.791 2c-3.142 0-3.963 1.77-4.15 2.562c-.282 1.197 0 2.141.625 2.594c.649.47 1.423.332 1.932.017c.389-.24.594-.646.594-1.173a1 1 0 1 1 2 0c0 1.221-.562 2.269-1.542 2.874c-1.106.683-2.819.538-3.919-.077c-1.351-.756-2.061-2.623-1.589-4.619C24.358 1.562 26.62 0 29.791 0c2.908 0 5.186 1.703 5.945 4.445c.889 3.208-.522 6.667-3.431 8.412c-4 2.4-3.53 5.962-3.525 5.998A1 1 0 0 1 27.79 20");
}

.u8sibbwvn {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M31 21h-6v9h6s2 0 2-2v-5c0-2-2-2-2-2");
}

</style>
