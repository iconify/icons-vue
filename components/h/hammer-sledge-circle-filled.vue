<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGcD7bgePu"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="so1mb-boo"/><path class="yb-s07b1w"/></g></mask></defs><circle mask="url(#SVGcD7bgePu)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:hammer-sledge-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.so1mb-boo {
  d: path("M13.033 3.555a2 2 0 0 1 1.225.43l6.863 5.416a2 2 0 0 1 .703 1.091l.19.774a2 2 0 0 1-.371 1.717l-2.492 3.158a2 2 0 0 1-1.584.76l-.796-.005a2 2 0 0 1-1.225-.43L8.683 11.05a2 2 0 0 1-.703-1.09l-.19-.774a2 2 0 0 1 .371-1.718l2.492-3.157a2 2 0 0 1 1.584-.761zm6.85 7.416l-6.864-5.416l-.796-.005L9.73 8.707l.19.773l6.864 5.416l.796.006l2.492-3.158z");
}

.yb-s07b1w {
  d: path("m12.028 13.061l-5.262 6.668l.785.62l5.262-6.669l1.57 1.24l-5.262 6.667a2 2 0 0 1-2.809.331l-.785-.62a2 2 0 0 1-.33-2.808l5.26-6.668zm4.491-5.691l.93-1.178l.784.62l-.93 1.177l1.571 1.239l.93-1.178a2 2 0 0 0-.332-2.809l-.785-.619a2 2 0 0 0-2.809.331l-.93 1.178z");
}

</style>
