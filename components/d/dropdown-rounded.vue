<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="runum65ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dropdown-rounded" /></template>
<style>
.runum65ym {
  fill: currentColor;
  d: path("M12.808 12h4.384q.348 0 .578-.23t.23-.578V6.808q0-.348-.23-.578T17.192 6h-4.384q-.349 0-.578.23t-.23.578v4.384q0 .349.23.578t.578.23m-7.192 8q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
