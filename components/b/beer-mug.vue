<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tqk_94n7p"/><path class="nafbacceg"/><path class="kixpczmgg"/><path class="tfnvfpb1o"/><path class="cqx6lgb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:beer-mug" /></template>
<style>
.cqx6lgb2c {
  fill: var(--svg-color--eee, #eee);
  d: path("M24 0H4a3 3 0 0 0-3 3v4a4 4 0 0 0 7.701 1.509C9.051 8.811 9.502 9 10 9c.677 0 1.273-.338 1.635-.853A3.99 3.99 0 0 0 15 10a3.98 3.98 0 0 0 3.176-1.593A2.5 2.5 0 0 0 20.5 10c.949 0 1.765-.535 2.188-1.314c.398.195.839.314 1.312.314a3 3 0 0 0 3-3V3a3 3 0 0 0-3-3");
}

.kixpczmgg {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M8.5 32a1 1 0 0 1-1-1V15a1 1 0 0 1 2 0v16a1 1 0 0 1-1 1m6.5 0a1 1 0 0 1-1-1V15a1 1 0 0 1 2 0v16a1 1 0 0 1-1 1m6.5 0a1 1 0 0 1-1-1V15a1 1 0 1 1 2 0v16a1 1 0 0 1-1 1");
}

.nafbacceg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M27 6H3v26a4 4 0 0 0 4 4h16a4 4 0 0 0 4-4z");
}

.tfnvfpb1o {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M3 5v7.445c.59.344 1.268.555 2 .555a4 4 0 0 0 3.701-2.491c.35.302.801.491 1.299.491c.677 0 1.273-.338 1.635-.853A3.99 3.99 0 0 0 15 12a3.98 3.98 0 0 0 3.176-1.593A2.5 2.5 0 0 0 20.5 12c.949 0 1.765-.535 2.188-1.314l.147-.361a3.46 3.46 0 0 0 1.665.439c.981 0 1.865-.406 2.5-1.056V5z");
}

.tqk_94n7p {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M31 5.718h-6v4h4s2 0 2 2v12c0 2-2 2-2 2h-4v4h6c2.206 0 4-1.794 4-4v-16c0-2.206-1.794-4-4-4");
}

</style>
