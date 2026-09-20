<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ov8egm-xs"/><path class="ml7g-npdq"/><path class="l34burw7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:curling-stone" /></template>
<style>
.l34burw7n {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M0 20h36v5H0z");
}

.ml7g-npdq {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M36 25a6 6 0 0 1-6 6H6a6 6 0 0 1-6-6v-5a6 6 0 0 1 6-6h24a6 6 0 0 1 6 6z");
}

.ov8egm-xs {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M28 12H13V8a1 1 0 0 1 1-1h11a2 2 0 0 0 0-4H14a5 5 0 0 0-5 5v4H8a2 2 0 0 0 0 4h20a2 2 0 0 0 0-4");
}

</style>
