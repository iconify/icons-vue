<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li7zx5lkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:humidity-percentage-sharp" /></template>
<style>
.li7zx5lkp {
  fill: currentColor;
  d: path("M14.822 16.825q.294-.292.294-.707q0-.416-.291-.71q-.292-.292-.707-.292q-.416 0-.71.29t-.292.707t.29.709t.707.294t.709-.291m-5.372.413l5.789-5.788l-.689-.708l-5.808 5.808zm1.141-4.645q.294-.29.294-.706t-.291-.709q-.291-.294-.707-.294t-.709.291q-.294.292-.294.707q0 .416.292.71q.29.292.706.292t.71-.29m-3.593 6.343Q5 16.873 5 13.8q0-2.154 1.738-4.765T12 3.308q3.525 3.117 5.262 5.728Q19 11.646 19 13.8q0 3.073-2.002 5.137Q14.994 21 11.996 21t-4.998-2.064");
}

</style>
