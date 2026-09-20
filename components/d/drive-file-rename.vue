<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt318-b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-file-rename" /></template>
<style>
.gt318-b_b {
  fill: currentColor;
  d: path("M11.283 16.5h6.333v-1h-5.333zm-4.898 0h2.21l6.5-6.5q.147-.148.2-.31t.051-.323t-.064-.319q-.065-.16-.188-.308l-.925-.944q-.129-.129-.298-.193t-.335-.064q-.159 0-.319.061q-.16.062-.308.19l-6.525 6.5zm7.151-6.177l-.95-.95l.95-.95l.926.944zM5.617 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
