<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuhgydf_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:doorbell-outline-rounded" /></template>
<style>
.kuhgydf_l {
  fill: currentColor;
  d: path("M12.626 16.991q.259-.239.297-.606h-1.846q.039.367.297.606q.259.24.626.24t.626-.24m-3.934-1.106h6.616q.154 0 .269-.112q.115-.111.115-.273t-.115-.273t-.27-.111h-.615v-2.272q0-1.063-.532-1.934q-.533-.871-1.525-1.14v-.328q0-.275-.184-.454q-.184-.18-.451-.18t-.451.18t-.183.454v.327q-.993.27-1.526 1.14q-.532.87-.532 1.934v2.273h-.616q-.154 0-.269.111q-.115.112-.115.273t.115.273t.27.112M5 18.385v-8.077q0-.384.172-.727t.474-.565l5.385-4.058q.223-.162.466-.243t.507-.08t.504.08t.461.243l5.385 4.057q.303.222.474.566q.172.343.172.727v8.077q0 .666-.475 1.14t-1.14.475H6.615q-.666 0-1.14-.475T5 18.386M6.616 19h10.769q.269 0 .442-.173t.173-.442v-8.077q0-.154-.067-.28t-.183-.22l-5.384-4.039q-.154-.134-.366-.134t-.365.134L6.25 9.808q-.115.096-.183.22t-.067.28v8.077q0 .269.173.442t.443.173M12 12.308");
}

</style>
