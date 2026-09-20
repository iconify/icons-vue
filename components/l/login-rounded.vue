<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd_pi_j-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:login-rounded" /></template>
<style>
.fd_pi_j-b {
  fill: currentColor;
  d: path("M12.48 20q-.213 0-.356-.143t-.143-.357t.143-.357t.357-.143h5.904q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5h-5.903q-.214 0-.357-.143t-.143-.357t.143-.357t.357-.143h5.904q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm.407-7.5H4.518q-.213 0-.356-.143T4.019 12t.144-.357t.356-.143h8.368l-1.972-1.971q-.14-.14-.15-.338q-.01-.199.15-.364t.354-.168q.195-.003.36.162l2.613 2.613q.243.243.243.566t-.243.566l-2.613 2.613q-.146.146-.346.153t-.364-.159q-.159-.165-.156-.357t.161-.35z");
}

</style>
