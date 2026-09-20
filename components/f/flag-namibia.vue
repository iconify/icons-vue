<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hgeeidl8n"/><path class="hp_fl4r0p"/><path class="c7mdjnnku"/><path class="yo5dodkqh"/><path class="gqiiqx62f"/><circle class="ee22wbbhy"/><circle class="ep558bc-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-namibia" /></template>
<style>
.c7mdjnnku {
  fill: var(--svg-color--eee, #eee);
  d: path("M36 9a4 4 0 0 0-4-4h-.664L0 26.942V27a4 4 0 0 0 4 4h.664L36 9.059z");
}

.ee22wbbhy {
  cx: 8px;
  cy: 13px;
  r: 3.175px;
  fill: var(--svg-color--003580, #003580);
}

.ep558bc-r {
  cx: 8px;
  cy: 13px;
  r: 2.467px;
  fill: var(--svg-color--ffce00, #ffce00);
}

.gqiiqx62f {
  fill: var(--svg-color--ffce00, #ffce00);
  d: path("m8 8l.809 1.981L10.5 8.67l-.29 2.12l2.12-.29l-1.311 1.691L13 13l-1.981.809L12.33 15.5l-2.12-.29l.29 2.12l-1.691-1.311L8 18l-.809-1.981L5.5 17.33l.29-2.12l-2.12.29l1.311-1.691L3 13l1.981-.809L3.67 10.5l2.12.29l-.29-2.12l1.691 1.311z");
}

.hgeeidl8n {
  fill: var(--svg-color--009543, #009543);
  d: path("M1.067 29.701A3.97 3.97 0 0 0 4 31h28a4 4 0 0 0 4-4V9a3.97 3.97 0 0 0-1.019-2.643z");
}

.hp_fl4r0p {
  fill: var(--svg-color--003580, #003580);
  d: path("M34.933 6.299A3.97 3.97 0 0 0 32 5H4a4 4 0 0 0-4 4v18a3.97 3.97 0 0 0 1.019 2.643z");
}

.yo5dodkqh {
  fill: var(--svg-color--d20f34, #d20f34);
  d: path("M32.984 5.136L.175 28.108a3.99 3.99 0 0 0 2.912 2.777L35.843 7.949a3.99 3.99 0 0 0-2.859-2.813");
}

</style>
