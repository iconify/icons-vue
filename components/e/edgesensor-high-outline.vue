<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmvwdrbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edgesensor-high-outline" /></template>
<style>
.dmvwdrbgs {
  fill: currentColor;
  d: path("M8.423 20q-.666 0-1.14-.475t-.475-1.14V5.615q0-.666.474-1.14T8.423 4h7.154q.666 0 1.14.475t.475 1.14v12.77q0 .666-.474 1.14T15.577 20zm7.77-1.616V5.616q0-.27-.174-.443Q15.846 5 15.577 5H8.423q-.27 0-.442.173q-.173.173-.173.443v12.769q0 .269.173.442t.442.173h7.154q.27 0 .442-.173q.173-.173.173-.442M12.588 8.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M1.462 16.5v-6h1v6zm2.769-3v-6h1v6zm17.307 0v-6h1v6zm-2.769 3v-6h1v6zM7.808 18.385V19V5z");
}

</style>
