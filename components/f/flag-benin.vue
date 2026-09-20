<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k7j4bsvxp"/><path class="dmqxilbra"/><path class="d678mplsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-benin" /></template>
<style>
.d678mplsj {
  fill: var(--svg-color--008751, #008751);
  d: path("M14 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h10z");
}

.dmqxilbra {
  fill: var(--svg-color--e8112d, #e8112d);
  d: path("M14 31h18a4 4 0 0 0 4-4v-9H14z");
}

.k7j4bsvxp {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M32 5H14v13h22V9a4 4 0 0 0-4-4");
}

</style>
