<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi3nyyy_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ballot" /></template>
<style>
.yi3nyyy_t {
  fill: currentColor;
  d: path("M12 10h4.616V9H12zm0 5h4.616v-1H12zm-2.126-4.626q.357-.357.357-.874t-.357-.874T9 8.269t-.874.357t-.357.874t.357.874t.874.357t.874-.357m0 5q.357-.357.357-.874t-.357-.874T9 13.269t-.874.357t-.357.874t.357.874t.874.357t.874-.357M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
