<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tx2-791kd"/><path class="cvw97ccnn"/><path class="n407rwkwa"/><path class="e1es0gbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cityscape" /></template>
<style>
.cvw97ccnn {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M10 36V7l4-4h2l4 4v29zm23-25c0-1-1-1-1-1h-7s-1 0-1 1v25h9z");
}

.e1es0gbnt {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M8 29h2v2H8zm0-8h2v2H8zm-2 4h2v2H6zM16 9h2v2h-2zm0 4h2v2h-2zm-2 4h2v2h-2zm10 1h2v2h-2zm-2 4h2v2h-2zm-2 6h2v2h-2zm9-16h2v2h-2zm0 4h2v2h-2z");
}

.n407rwkwa {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M28 17c0-1-1-1-1-1h-8c-1 0-1 1-1 1v19h10zm-17 2H6v-5s0-1-1-1H0v19a4 4 0 0 0 4 4h8V20s0-1-1-1m21 6c-1 0-1 1-1 1v10h1a4 4 0 0 0 4-4v-7z");
}

.tx2-791kd {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M32 0H4a4 4 0 0 0-4 4v22h36V4a4 4 0 0 0-4-4");
}

</style>
