<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG2SkQcesi"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="sgqc3hb7l"/><path class="zyct2abjb"/></g></mask></defs><circle mask="url(#SVG2SkQcesi)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:label-circle-filled" /></template>
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

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.sgqc3hb7l {
  fill-rule: evenodd;
  d: path("M7.91 7.564c-.018.283-.034.596-.047.927c-.054 1.358-.047 2.907.102 4.078l7.265 7.265l4.95-4.95l-7.265-7.265c-1.17-.149-2.72-.156-4.078-.102c-.331.013-.643.03-.927.047M6.094 5.748c-.097.092-.49 4.567-.077 7.33c.044.294.189.56.399.77l7.753 7.754a1.5 1.5 0 0 0 2.122 0l5.657-5.657a1.5 1.5 0 0 0 0-2.122L14.194 6.07a1.4 1.4 0 0 0-.77-.4c-2.763-.411-7.238-.02-7.33.078");
}

.zyct2abjb {
  d: path("M12.142 10.466a1 1 0 1 1-1.415 1.414a1 1 0 0 1 1.415-1.414");
}

</style>
