<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg26bskfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:featured-seasonal-and-gifts-outline-rounded" /></template>
<style>
.hg26bskfd {
  fill: currentColor;
  d: path("M4.23 19.385V10.23h-.192q-.44 0-.739-.3T3 9.193V6.846q0-.44.299-.74t.74-.298h4.103q-.298-.264-.412-.63q-.114-.365-.114-.755q0-1 .692-1.692T10 2.039q.575 0 1.056.27q.48.27.829.703q.348-.439.828-.706t1.056-.267q1 0 1.692.692t.693 1.692q0 .39-.118.753t-.409.632h4.335q.44 0 .739.299t.299.74v2.345q0 .44-.299.74t-.74.299h-.192v9.154q0 .67-.472 1.143q-.472.472-1.143.472H5.846q-.671 0-1.143-.472t-.472-1.144m8.557-15.943q-.403.403-.403.982t.403.982t.981.403t.982-.403t.403-.982t-.403-.982q-.403-.402-.982-.402t-.981.402m-4.172.982q0 .579.402.982q.403.403.982.403t.982-.403t.403-.982t-.403-.982Q10.579 3.04 10 3.04t-.982.402t-.403.982M4 6.808V9.23h7.5V6.808zM11.5 20v-9.77H5.23v9.155q0 .269.174.442q.173.173.442.173zm1 0h5.654q.269 0 .442-.173t.173-.442V10.23H12.5zM20 9.23V6.809h-7.5V9.23z");
}

</style>
