<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky4payb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-rook-outline-sharp" /></template>
<style>
.ky4payb7p {
  fill: currentColor;
  d: path("M5 21v-4.192q1.929-1.568 2.848-3.295t1.479-3.84H6.866V3h3.788v2.827h2.712V3h3.788v6.673h-2.487q.58 2.114 1.48 3.84T19 16.809V21zm1-1h12v-2.71q-1.88-1.661-2.864-3.539T13.63 9.673h-3.267q-.516 2.2-1.502 4.078q-.987 1.878-2.862 3.54zM7.866 8.673h8.288V4h-1.789v2.827H9.654V4H7.866zm0 0h8.288z");
}

</style>
