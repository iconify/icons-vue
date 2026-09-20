<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crkq2z57l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-circle-outline-rounded" /></template>
<style>
.crkq2z57l {
  fill: currentColor;
  d: path("M11.5 10.921v9.156q0 .213.144.356t.357.144t.356-.144t.143-.356v-9.156l2.766 2.721q.14.14.34.134t.351-.153q.137-.134.137-.341t-.14-.348l-3.389-3.368q-.242-.243-.565-.243t-.565.243l-3.389 3.388q-.14.14-.133.341t.156.35q.137.138.331.138t.335-.14zM6.325 6.325Q4 8.65 4 12q0 .844.172 1.657t.517 1.576q.097.213.065.428q-.032.214-.198.378q-.154.152-.37.085q-.217-.066-.307-.272q-.437-.91-.658-1.871Q3 13.019 3 12q0-1.868.709-3.51T5.63 5.633t2.857-1.924T11.997 3t3.51.709q1.643.708 2.859 1.923t1.925 2.857t.709 3.508q0 1.013-.228 2.004t-.67 1.901q-.09.2-.288.244q-.197.045-.343-.102q-.165-.165-.195-.369t.049-.411q.35-.785.512-1.607T20 12q0-3.35-2.325-5.675T12 4T6.325 6.325");
}

</style>
