<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k-e0-2-ap"/><path class="t-tua9xey"/><path class="ep6e8abtu"/><path class="z8tnnlb5h"/><path class="bp9sff8tt"/><circle class="ee22wbbhy"/><circle class="wp0_iwxtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-namibia" /></template>
<style>
.bp9sff8tt {
  fill: var(--svg-color--ffce00, #FFCE00);
  d: path("M8 8l.809 1.981L10.5 8.67l-.29 2.12l2.12-.29l-1.311 1.691L13 13l-1.981.809L12.33 15.5l-2.12-.29l.29 2.12l-1.691-1.311L8 18l-.809-1.981L5.5 17.33l.29-2.12l-2.12.29l1.311-1.691L3 13l1.981-.809L3.67 10.5l2.12.29l-.29-2.12l1.691 1.311z");
}

.ee22wbbhy {
  fill: var(--svg-color--003580, #003580);
  cx: 8px;
  cy: 13px;
  r: 3.175px;
}

.ep6e8abtu {
  fill: var(--svg-color--eee, #EEE);
  d: path("M36 9a4 4 0 0 0-4-4h-.664L0 26.942V27a4 4 0 0 0 4 4h.664L36 9.059V9z");
}

.k-e0-2-ap {
  fill: var(--svg-color--009543, #009543);
  d: path("M1.067 29.701A3.973 3.973 0 0 0 4 31h28a4 4 0 0 0 4-4V9a3.97 3.97 0 0 0-1.019-2.643L1.067 29.701z");
}

.t-tua9xey {
  fill: var(--svg-color--003580, #003580);
  d: path("M34.933 6.299A3.973 3.973 0 0 0 32 5H4a4 4 0 0 0-4 4v18a3.97 3.97 0 0 0 1.019 2.643L34.933 6.299z");
}

.wp0_iwxtl {
  fill: var(--svg-color--ffce00, #FFCE00);
  cx: 8px;
  cy: 13px;
  r: 2.467px;
}

.z8tnnlb5h {
  fill: var(--svg-color--d20f34, #D20F34);
  d: path("M32.984 5.136L.175 28.108a3.988 3.988 0 0 0 2.912 2.777L35.843 7.949a3.986 3.986 0 0 0-2.859-2.813z");
}

</style>
