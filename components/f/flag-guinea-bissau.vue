<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="l23u5sdab"/><path class="zazgdjcah"/><path class="ialijvcdr"/><path class="axtitjbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-guinea-bissau" /></template>
<style>
.axtitjbbf {
  d: path("m8.426 17.155l-.973-2.994l-.973 2.994H3.332l2.547 1.851L4.906 22l2.547-1.851L10 22l-.973-2.994l2.547-1.851z");
}

.ialijvcdr {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M15 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h11zm-5 17l-2.547-1.851L4.906 22l.973-2.994l-2.547-1.851H6.48l.973-2.994l.973 2.994h3.148l-2.547 1.851z");
}

.l23u5sdab {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M32 5H15v13h21V9a4 4 0 0 0-4-4");
}

.zazgdjcah {
  fill: var(--svg-color--009e49, #009e49);
  d: path("M15 31h17a4 4 0 0 0 4-4v-9H15z");
}

</style>
