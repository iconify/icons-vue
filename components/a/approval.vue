<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyzrfsbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:approval" /></template>
<style>
.cyzrfsbzj {
  fill: currentColor;
  d: path("M5 19.462V15q0-.69.463-1.153t1.153-.462h10.769q.69 0 1.153.462T19 15v4.462zm1-3h12V15q0-.23-.192-.423t-.424-.192H6.616q-.231 0-.424.192T6 15zm6-3.077L8 7.962v-.193q0-1.671 1.165-2.835Q10.329 3.769 12 3.769t2.836 1.165T16 7.769v.192z");
}

</style>
