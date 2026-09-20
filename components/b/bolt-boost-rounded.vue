<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waox7ih-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bolt-boost-rounded" /></template>
<style>
.waox7ih-e {
  fill: currentColor;
  d: path("M13.69 19.379q-.069-.11-.044-.27l.816-5.648h-3.877q-.49 0-.727-.444t.055-.848l5.502-7.571q.106-.13.23-.159t.255.022t.199.16t.043.27l-.815 5.667h3.877q.49 0 .717.444t-.065.848l-5.483 7.552q-.106.13-.23.159t-.255-.022t-.198-.16M4.5 17.25q-.213 0-.356-.144T4 16.749t.144-.356t.356-.143h6.646q.25 0 .375.155t.125.341t-.125.345t-.375.159zm-1-4.75q-.213 0-.356-.144T3 11.999t.144-.356t.356-.143h3q.25 0 .375.155t.125.342t-.125.344t-.375.159zm1.98-4.75q-.212 0-.355-.144t-.144-.357t.144-.356t.356-.143h4.548q.25 0 .375.155t.125.341t-.125.345t-.375.159z");
}

</style>
