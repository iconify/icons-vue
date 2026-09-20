<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tphowdbaj"/><path class="hvyf6-byu"/><path class="i5k-7_b8p"/><path class="xynbcabup"/><path class="hah1kqbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arbitrum" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hah1kqbjx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.433 7.635H9.731a.3.3 0 0 0-.285.197l-3.649 9.852l1.761 1.001l4.018-10.849a.15.15 0 0 0-.143-.2m2.979-.001h-1.703a.3.3 0 0 0-.284.197l-4.167 11.25l1.761 1l4.535-12.246a.15.15 0 0 0-.142-.2");
}

.hvyf6-byu {
  fill: var(--svg-color--12aaff, #12aaff);
  d: path("m13.353 13.368l-.885 2.39a.3.3 0 0 0 0 .205l1.523 4.112l1.76-1.001l-2.113-5.706a.152.152 0 0 0-.285 0m1.774-4.019a.152.152 0 0 0-.285 0l-.885 2.39a.3.3 0 0 0 0 .205l2.494 6.732l1.761-1.001z");
}

.i5k-7_b8p {
  fill: var(--svg-color--9dcced, #9dcced);
  d: path("M11.998 4.115a.3.3 0 0 1 .126.033l6.715 3.818a.25.25 0 0 1 .126.214v7.635c0 .089-.048.17-.126.214l-6.715 3.819a.25.25 0 0 1-.126.032a.3.3 0 0 1-.125-.032l-6.715-3.815a.25.25 0 0 1-.126-.215V8.182c0-.089.048-.17.126-.215l6.715-3.818a.26.26 0 0 1 .125-.034m0-1.115c-.238 0-.478.06-.692.183L4.593 7A1.36 1.36 0 0 0 3.9 8.182v7.635c0 .487.264.938.693 1.181l6.714 3.819a1.41 1.41 0 0 0 1.386 0l6.714-3.818a1.36 1.36 0 0 0 .693-1.182V8.182A1.36 1.36 0 0 0 19.407 7l-6.716-3.817A1.4 1.4 0 0 0 11.998 3");
}

.tphowdbaj {
  fill: var(--svg-color--213147, #213147);
  d: path("M4.515 8.471v7.056c0 .45.245.867.64 1.092l6.205 3.529a1.3 1.3 0 0 0 1.28 0l6.203-3.53c.396-.224.64-.64.64-1.09V8.47c0-.45-.244-.867-.64-1.091L12.64 3.85a1.3 1.3 0 0 0-1.28 0L5.155 7.38a1.25 1.25 0 0 0-.639 1.091");
}

.xynbcabup {
  fill: var(--svg-color--213147, #213147);
  d: path("m7.559 18.685l.617-1.666l1.244 1.018l-1.163 1.046z");
}

</style>
