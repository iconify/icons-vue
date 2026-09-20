<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kpfq32bkq"/><path class="q-pgl_b7n"/><path class="t4289tb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-private-opened" /></template>
<style>
.kpfq32bkq {
  fill: var(--svg-color--a76571, #a76571);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.q-pgl_b7n {
  fill: var(--svg-color--a76571, #a76571);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.t4289tb5o {
  fill: var(--svg-color--d80027, #d80027);
  d: path("M20.4 10a10.5 10.5 0 1 0 10.5 10.5A10.5 10.5 0 0 0 20.4 10m0 18.375a7.862 7.862 0 0 1-6.41-12.432l10.968 10.968a7.83 7.83 0 0 1-4.558 1.464m6.411-3.318L15.843 14.09a7.862 7.862 0 0 1 10.968 10.967");
}

</style>
