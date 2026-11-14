<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb9bghocj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-truck" /></template>
<style>
.nb9bghocj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.375 3.75h-6.25q-3.375 0-3.375 3.375v5.75q0 3.375 3.375 3.375h.03q-.905.673-.905 2.25q0 2.75 2.75 2.75t2.75-2.75q0-1.577-.905-2.25h2.53q1.185 0 1.954-.416q.046.094.117.171q.07.078.159.133t.19.083q.1.029.205.029h1.655q-.905.673-.905 2.25q0 2.75 2.75 2.75t2.75-2.75q0-1.577-.905-2.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-.149-.057-.287t-.163-.243l-3.5-3.5q-.105-.106-.243-.163T18 7.75h-3.25v-.625q0-3.375-3.375-3.375m9.375 11h-6.375q.375-.75.375-1.875V9.25h2.939l3.061 3.061z");
}

</style>
