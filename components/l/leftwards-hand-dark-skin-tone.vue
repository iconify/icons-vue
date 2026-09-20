<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="aoq0czjxx"/><path class="x29lf2b-u"/><path class="lw08jebkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:leftwards-hand-dark-skin-tone" /></template>
<style>
.aoq0czjxx {
  fill: var(--svg-color--583529, #583529);
  d: path("M2.965 15.5a2.5 2.5 0 0 0 2.5 2.5h.005L.465 20.5a2.5 2.5 0 0 0 2.5 2.5H4.25l-1.535 2.5a2.5 2.5 0 0 0 2.5 2.5H8.75L18 29V15.458z");
}

.lw08jebkq {
  fill: var(--svg-color--583529, #583529);
  d: path("M21.471 12.561c-.266.297-.552.372-.808.417c.259 1.892.789 4.457 2.715 6.427c2.499 2.556 5.2 2.992 7.007 2.971c1.457-.017 2.147-.812-.012-1.045c-2.706-.292-8.063-2.254-8.58-8.784l-.035-.591s-.06.352-.287.605");
}

.x29lf2b-u {
  fill: var(--svg-color--7c533e, #7c533e);
  d: path("M16.219 4.625c-.611 1.381.208 3.354 2.188 4.75c1.3.917 3.151 1.187 3.344 2.391c.073.46-.313 1.234-1.397 1.234H4.5s-2 0-2 2s2 2 2 2h11.633c-.029 0-.064 1-.082 1H2s-2 0-2 2s2 2 2 2h14.053c.017 0 .041 1 .069 1H4.25s-2 0-2 2s2 2 2 2h12.638c.118 0 .251 1 .398 1H8.75s-2 0-2 2s2 2 2 2H24c6.627 0 12-5.373 12-12c0-4.775-2.598-8.06-5.292-9.896C28.423 8.547 26.051 8.096 25.334 8c0 0-1.479-.123-2.865-1.156a58 58 0 0 1-3.866-3.125c-.359-.317-1.707-.625-2.384.906");
}

</style>
