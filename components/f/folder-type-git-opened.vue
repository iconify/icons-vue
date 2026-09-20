<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drz4-pb8k"/><path class="kg_0zpb1m"/><path class="pp_s_unun"/><path class="e7_mrfzir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-git-opened" /></template>
<style>
.drz4-pb8k {
  fill: var(--svg-color--db847b, #db847b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.e7_mrfzir {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.619 12.3l2.415 2.415a1.606 1.606 0 0 1 2.034 2.047l2.332 2.329a1.607 1.607 0 1 1-.964.907l-2.176-2.171v5.713a1.606 1.606 0 1 1-1.323-.047v-5.766a1.61 1.61 0 0 1-.873-2.11l-2.381-2.381");
}

.kg_0zpb1m {
  fill: var(--svg-color--db847b, #db847b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.pp_s_unun {
  fill: var(--svg-color--dd4c35, #dd4c35);
  d: path("M30.6 19.565L21.435 10.4a1.35 1.35 0 0 0-1.913 0l-1.9 1.9l2.415 2.415a1.606 1.606 0 0 1 2.034 2.047l2.329 2.329a1.607 1.607 0 1 1-.964.907l-2.176-2.171v5.713a1.606 1.606 0 1 1-1.323-.047v-5.766a1.61 1.61 0 0 1-.873-2.11l-2.381-2.381l-6.283 6.286a1.353 1.353 0 0 0 0 1.913l9.165 9.165a1.353 1.353 0 0 0 1.913 0l9.122-9.122a1.353 1.353 0 0 0 0-1.913");
}

</style>
