<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdqklobmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chrome-reader-mode" /></template>
<style>
.rdqklobmu {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm7.884-1h6.885q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H12.5zm1.077-3.308h5.346v-.884h-5.346zm0-2.5h5.346v-.884h-5.346zm0-2.5h5.346v-.884h-5.346z");
}

</style>
