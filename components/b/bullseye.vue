<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="kj73mib-f"/><circle class="qbsltm5ip"/><circle class="er5d0w1tl"/><circle class="caegj6bwy"/><circle class="runk7x7cj"/><path class="abg8gfoxj"/><path class="d1-yf0b5u"/><path class="k32ub2bom"/><path class="dkl062nwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bullseye" /></template>
<style>
.abg8gfoxj {
  d: path("m18.24 18.282l13.144 11.754s-2.647 3.376-7.89 5.109L17.579 18.42z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.caegj6bwy {
  cx: 18px;
  cy: 18px;
  r: 6px;
  fill: var(--svg-color--fff, #fff);
}

.d1-yf0b5u {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18.294 19a.994.994 0 0 1-.704-1.699l.563-.563a.995.995 0 0 1 1.408 1.407l-.564.563a1 1 0 0 1-.703.292");
}

.dkl062nwy {
  fill: var(--svg-color--3a87c2, #3a87c2);
  d: path("M32.798 4.485L21.176 17.587c-.362.362-1.673.882-2.51.046s-.419-2.08-.057-2.443L31.815 3.501s.676-.635 1.159-.152s-.176 1.136-.176 1.136");
}

.er5d0w1tl {
  cx: 18px;
  cy: 18px;
  r: 10px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.k32ub2bom {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M24.016 6.981c-.403 2.079 0 4.691 0 4.691l7.054-7.388c.291-1.454-.528-3.932-1.718-4.238s-4.079.803-5.336 6.935m5.003 5.003c-2.079.403-4.691 0-4.691 0l7.388-7.054c1.454-.291 3.932.528 4.238 1.718s-.803 4.079-6.935 5.336");
}

.kj73mib-f {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.qbsltm5ip {
  cx: 18px;
  cy: 18px;
  r: 13.5px;
  fill: var(--svg-color--fff, #fff);
}

.runk7x7cj {
  cx: 18px;
  cy: 18px;
  r: 3px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

</style>
