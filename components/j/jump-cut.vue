<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ukxbc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jump-cut" /></template>
<style>
.p9ukxbc3g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.5 4.75h-6q-1.139 0-1.945.805q-.805.806-.805 1.945v9q0 2.75 2.75 2.75h6q.165 0 .314-.069q.136-.063.237-.172q.101-.11.153-.25t.045-.289t-.068-.284L9.826 15.25l1.355-2.936q.069-.149.069-.314t-.069-.314L9.826 8.75l1.355-2.936q.069-.149.069-.314q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m2.569.436q.045-.098.116-.179q.07-.081.161-.139q.09-.058.193-.088t.211-.03h5.75q2.75 0 2.75 2.75v9q0 2.75-2.75 2.75h-5.75q-.107 0-.211-.03q-.103-.03-.193-.088t-.161-.139t-.116-.179l-1.5-3.25q-.069-.149-.069-.314t.069-.314L12.924 12l-1.355-2.936q-.069-.149-.069-.314t.069-.314z");
}

</style>
