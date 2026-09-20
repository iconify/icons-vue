<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzfb54spw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-inset" /></template>
<style>
.xzfb54spw {
  fill: currentColor;
  d: path("M6.692 15.616h10.616q.134 0 .22-.087q.088-.087.088-.221V8.692q0-.134-.087-.22q-.087-.088-.221-.088H6.692q-.134 0-.22.087q-.087.087-.087.221v6.616q0 .134.086.22q.087.088.221.088M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm4-5.27l1.799-2.401l1.163 1.555l1.587-2.115l2.22 2.962z");
}

</style>
