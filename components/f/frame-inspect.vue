<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws-34tbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-inspect" /></template>
<style>
.ws-34tbbz {
  fill: currentColor;
  d: path("M13.004 13.004q.804-.804.804-1.946t-.804-1.946t-1.946-.804t-1.946.803t-.804 1.947t.803 1.946t1.947.804t1.946-.804m3.09 3.804l-2.76-2.78q-.5.384-1.071.582q-.573.198-1.205.198q-1.564 0-2.657-1.093t-1.093-2.657T8.4 8.4t2.657-1.093T13.714 8.4t1.094 2.657q0 .633-.201 1.205t-.584 1.072l2.785 2.765zM5.616 20q-.691 0-1.153-.462T4 18.384V15h1v3.385q0 .23.192.423t.423.192H9v1zM15 20v-1h3.385q.23 0 .423-.192t.192-.424V15h1v3.385q0 .69-.462 1.152T18.384 20zM4 9V5.616q0-.691.463-1.153T5.616 4H9v1H5.616q-.231 0-.424.192T5 5.616V9zm15 0V5.616q0-.231-.192-.424T18.384 5H15V4h3.385q.69 0 1.152.463T20 5.616V9z");
}

</style>
