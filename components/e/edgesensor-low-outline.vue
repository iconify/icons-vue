<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc35zvb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edgesensor-low-outline" /></template>
<style>
.sc35zvb8q {
  fill: currentColor;
  d: path("M8.423 20q-.671 0-1.143-.472t-.472-1.144V5.616q0-.672.472-1.144T8.423 4h7.154q.671 0 1.143.472t.472 1.143v12.77q0 .67-.472 1.143q-.472.472-1.143.472zm7.77-1.616V5.616q0-.27-.174-.443Q15.846 5 15.577 5H8.423q-.27 0-.442.173q-.173.173-.173.443v12.769q0 .269.173.442t.442.173h7.154q.27 0 .442-.173q.173-.173.173-.442M12.588 8.087q.22-.22.22-.548q0-.33-.22-.55t-.55-.22q-.328 0-.548.22t-.22.55t.22.549t.549.22q.328 0 .549-.22M4.23 13.5v-6h1v6zm14.538 3v-6h1v6zm-10.96 1.885V19V5z");
}

</style>
