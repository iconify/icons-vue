<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge4le0boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:id-card-outline" /></template>
<style>
.ge4le0boi {
  fill: currentColor;
  d: path("M14.154 12.462h4.077v-1h-4.077zm0-2.77h4.077v-1h-4.077zm-8.385 5.616h6.616v-.166q0-.875-.88-1.355t-2.428-.48t-2.429.48t-.879 1.355zm4.374-4.05q.434-.433.434-1.066t-.434-1.066t-1.066-.434t-1.066.434t-.434 1.066t.434 1.067t1.066.433t1.066-.433M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.77q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
