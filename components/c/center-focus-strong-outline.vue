<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bz7-rsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:center-focus-strong-outline" /></template>
<style>
.f0bz7-rsl {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V15h1v3.385q0 .23.192.423t.423.192H9v1zM15 20v-1h3.385q.23 0 .423-.192t.192-.424V15h1v3.385q0 .69-.462 1.152T18.384 20zM4 9V5.616q0-.691.463-1.153T5.616 4H9v1H5.616q-.231 0-.424.192T5 5.616V9zm15 0V5.616q0-.231-.192-.424T18.384 5H15V4h3.385q.69 0 1.152.463T20 5.616V9zm-9.835 5.836Q8 13.67 8 12t1.165-2.835T12 8t2.836 1.165T16 12t-1.164 2.836T12 16t-2.835-1.164m4.96-.711Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M12 12");
}

</style>
