<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trqszhnwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-install-outline" /></template>
<style>
.trqszhnwk {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V4.615q0-.69.463-1.152T4.615 3H12.5L17 7.5v5.039h-1V8h-4V4H4.616q-.231 0-.424.192T4 4.615v14.77q0 .23.192.423t.423.192h9.424v1zM4 20V4zm1.962-1.77q.08-.993.605-1.816t1.383-1.308l-.777-1.373q0-.006.08-.318q.088-.05.18-.03q.094.019.144.105l.783 1.404q.404-.161.807-.245q.404-.083.833-.083t.842.083t.799.245l.782-1.404q.02-.019.298-.08q.087.05.121.146q.035.096-.015.177l-.758 1.373q.858.485 1.373 1.308q.516.822.597 1.817zm2.504-1.332q.111-.121.111-.283t-.111-.282t-.274-.121t-.282.12t-.121.284t.12.282q.122.121.283.121t.274-.121m3.644 0q.12-.121.12-.283t-.12-.282q-.121-.121-.283-.121t-.283.12t-.121.284t.121.282t.283.121t.283-.121M18.539 21l-3.289-3.308l.689-.713l2.1 2.094v-4.861h1v4.861l2.1-2.075l.688.694z");
}

</style>
