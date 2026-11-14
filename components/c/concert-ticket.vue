<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwu4tcbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:concert-ticket" /></template>
<style>
.vwu4tcbis {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.375 4.75h-7.25q-3.375 0-3.375 3.375v7.75q0 3.375 3.375 3.375h7.25q3.375 0 3.375-3.375v-7.75q0-3.375-3.375-3.375m7.125 0h.25q1.036 0 1.768.732t.732 1.768v9.5q0 1.036-.732 1.768t-1.768.732h-.25q-1.036 0-1.768-.732T17 16.75v-9.5q0-2.5 2.5-2.5m-9.5 9.5q0 2.25-2.25 2.25T5.5 14.25T7.75 12q.413 0 .75.076V8.25q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.092 0 .182.022q3.629.908 3.314 4.053q-.007.073-.029.144q-.021.07-.056.136q-.035.065-.082.122t-.104.103q-.057.047-.122.082q-.066.035-.136.056t-.145.028q-.073.008-.147 0q-.073-.007-.144-.029q-.07-.021-.136-.056q-.065-.035-.122-.082t-.103-.104q-.047-.057-.082-.122q-.035-.066-.056-.136t-.028-.145q-.008-.073 0-.147q.144-1.44-1.254-2.12z");
}

</style>
