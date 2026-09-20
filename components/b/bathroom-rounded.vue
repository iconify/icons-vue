<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svy-l7blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bathroom-rounded" /></template>
<style>
.svy-l7blg {
  fill: currentColor;
  d: path("M9.549 17.548q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m3 0q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m3 0q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m-6-3q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m3 0q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m3 0q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221M9.039 7.77q-1.25 1.155-1.404 2.846q-.039.328.199.549q.238.22.589.22h7.154q.351 0 .589-.22t.2-.55q-.154-1.69-1.405-2.845T12 6.616T9.04 7.77M4.616 21q-.691 0-1.153-.462T3 19.385V4.615q0-.69.463-1.152T4.615 3h14.77q.69 0 1.152.463T21 4.616v14.769q0 .69-.463 1.153T19.385 21z");
}

</style>
