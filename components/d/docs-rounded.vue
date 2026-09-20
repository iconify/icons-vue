<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fne8nsa7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:docs-rounded" /></template>
<style>
.fne8nsa7o {
  fill: currentColor;
  d: path("M12 3v3.77q0 1 .683 1.701t1.644.702H18v10.212q0 .69-.462 1.153T16.384 21H7.616q-.691 0-1.153-.462T6 19.385V4.615q0-.69.463-1.152T7.616 3zm1 0h.654L18 7.462v.711h-3.673q-.579 0-.953-.413T13 6.77zm-2.846 15.173H12q.214 0 .357-.143t.143-.357t-.143-.357t-.357-.143h-1.846q-.213 0-.357.143q-.143.143-.143.357t.143.357t.357.143m0-3.788h3.673q.214 0 .357-.144t.143-.357t-.143-.356t-.357-.144h-3.673q-.213 0-.357.144q-.143.143-.143.357q0 .213.143.356q.144.144.357.144");
}

</style>
