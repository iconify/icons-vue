<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="p406iianx"/><path class="dkcxw_beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-sweden" /></template>
<style>
.dkcxw_beh {
  fill: var(--svg-color--fecc00, #fecc00);
  d: path("M15.5 5h-5v10.5H0v5h10.5V31h5V20.5H36v-5H15.5z");
}

.p406iianx {
  fill: var(--svg-color--006aa7, #006aa7);
  d: path("M15.5 31H32c2.209 0 4-1.791 4-4.5v-6H15.5zM32 5H15.5v10.5H36V9a4 4 0 0 0-4-4M10.5 5H4a4 4 0 0 0-4 3.997V15.5h10.5zM0 20.5v6.004C.002 29.211 1.792 31 4 31h6.5V20.5z");
}

</style>
