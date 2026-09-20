<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npch5bckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-install-outline-sharp" /></template>
<style>
.npch5bckm {
  fill: currentColor;
  d: path("M3 21V3h9.5L17 7.5v5.039h-1V8h-4V4H4v16h10.039v1zm1-1V4zm1.962-1.77q.08-.987.608-1.814t1.38-1.31l-.777-1.373q0-.006.075-.323q.092-.045.186-.026q.093.02.143.106l.783 1.404q.405-.155.811-.242t.832-.086t.84.083q.413.084.798.245l.782-1.403q.02-.02.293-.081q.092.05.126.146q.035.096-.006.177l-.767 1.373q.858.485 1.374 1.31q.516.827.595 1.815zm2.504-1.332q.111-.121.111-.283t-.111-.282t-.274-.121t-.282.12t-.121.284t.12.282q.122.121.283.121t.274-.121m3.644 0q.12-.121.12-.283t-.12-.282q-.121-.121-.283-.121t-.283.12t-.121.284t.121.282t.283.121t.283-.121M18.539 21l-3.289-3.308l.689-.713l2.1 2.094v-4.861h1v4.861l2.1-2.075l.688.694z");
}

</style>
