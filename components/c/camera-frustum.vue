<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lge2vkdbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-frustum" /></template>
<style>
.lge2vkdbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 11.625v.75q0 .339-.034.644l7.534 3.767V4.601l-7.545 6.288q.045.345.045.736m-.495 2.841q-.798 1.284-2.88 1.284h-.75q-3.375 0-3.375-3.375v-.75q0-3.375 3.375-3.375h.75q1.963 0 2.784 1.141l8.361-6.967q.099-.083.22-.128q.121-.044.25-.046h.01q.231 0 .422.13l.028.02l4 3q.07.052.126.119t.095.146t.059.163t.02.172v15q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.122 0-.237-.038q-.116-.039-.213-.112l-3.946-2.959z");
}

</style>
