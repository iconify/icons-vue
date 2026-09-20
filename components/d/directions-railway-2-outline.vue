<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_x9pb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:directions-railway-2-outline" /></template>
<style>
.yr_x9pb8f {
  fill: currentColor;
  d: path("m5 21l1.539-1.538h10.923L19 21zm2.308-2.308l.769-.769h-.25q-1.2 0-2.013-.842T5 15.038V8.192q0-2.84 2.024-4.516T12 2t4.976 1.676T19 8.192v6.847q0 1.2-.813 2.042t-2.014.842h-.25l.77.77zm.519-1.769h8.346q.76 0 1.293-.553q.534-.553.534-1.332v-3.884H6v3.885q0 .778.534 1.331q.533.553 1.293.553m5.101-1.957q.38-.38.38-.927t-.38-.928t-.928-.38t-.928.38t-.38.928t.38.927q.38.38.928.38t.928-.38M6 10.154h12V8.192q0-.613-.122-1.158T17.518 6H6.482q-.239.489-.361 1.034T6 8.192zM7.225 5h9.55q-.794-.961-2.035-1.48Q13.498 3 12 3t-2.74.52Q8.02 4.038 7.226 5M12 5");
}

</style>
