<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_cbf6bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:charcoal-bag" /></template>
<style>
.e_cbf6bds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.522 2.818l-.75 3q-.016.065-.02.132v.001l-1 14.999q-.01.149.038.29q.047.142.146.254t.232.178t.282.076l.05.002h15q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146l-.002-.05l-1-14.999v-.007q-.005-.064-.02-.126l-.75-3q-.016-.06-.04-.117q-.025-.058-.059-.11t-.076-.098t-.091-.084t-.104-.068t-.114-.05t-.12-.031q-.062-.01-.124-.01H6.25q-.062 0-.124.01q-.061.011-.12.031t-.114.05t-.104.068t-.091.084t-.076.098t-.059.11q-.024.057-.04.117M17.539 5.25H6.461l.375-1.5h10.328zm-5.07 3.164Q16.25 11.44 16.25 14.5q0 1.76-1.245 3.005T12 18.75t-3.005-1.245T7.75 14.5q0-1.727 2.373-4.421Q11 9.083 11.4 8.55q.044-.059.099-.108q.055-.05.119-.087q.063-.038.133-.063q.07-.024.143-.034t.147-.007t.145.022t.138.051t.126.076z");
}

</style>
