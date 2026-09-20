<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ve9u_4w-c"/><path class="jd-p6o-fp"/><path class="t45xghqgs"/><path class="c89x9ab6u"/><path class="e9ufznbwv"/><path class="l4ipvvkgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:card-index" /></template>
<style>
.c89x9ab6u {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M30 32a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V21a2 2 0 0 1 2-2h20a2 2 0 0 1 2 2z");
}

.e9ufznbwv {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M28 4a1 1 0 0 1-1 1h-6a1 1 0 1 1 0-2h6a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1h-6a1 1 0 1 1 0-2h6a1 1 0 0 1 1 1m0 4a1 1 0 0 1-1 1h-6a1 1 0 1 1 0-2h6a1 1 0 0 1 1 1");
}

.jd-p6o-fp {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M30 15a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h20a2 2 0 0 1 2 2z");
}

.l4ipvvkgu {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M14 20a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0zm10 0a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0z");
}

.t45xghqgs {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M18 13a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1z");
}

.ve9u_4w-c {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M32 13H4a4 4 0 0 0-4 4v2a4 4 0 0 0 4 4v9a4 4 0 0 0 4 4h20a4 4 0 0 0 4-4v-9a4 4 0 0 0 4-4v-2a4 4 0 0 0-4-4");
}

</style>
