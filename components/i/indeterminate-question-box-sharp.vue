<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4m_k0_ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:indeterminate-question-box-sharp" /></template>
<style>
.q4m_k0_ug {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V15h1v3.385q0 .23.192.423t.423.192H9v1zm12.769 0H15v-1h3.385q.23 0 .423-.192t.192-.424V15h1v3.385q0 .69-.462 1.152T18.384 20M4 5.616q0-.691.463-1.153T5.616 4H9v1H5.616q-.231 0-.424.192T5 5.616V9H4zm16 0V9h-1V5.616q0-.231-.192-.424T18.384 5H15V4h3.385q.69 0 1.152.463T20 5.616m-7.401 11.368q.228-.228.228-.561q0-.332-.228-.56t-.56-.228t-.561.228t-.228.56t.228.56q.228.229.56.229t.561-.228m-1.076-3.078h.96q.038-.639.248-1.05t.807-1.01q.76-.76 1.047-1.278t.288-1.152q0-1.158-.783-1.893q-.782-.734-2.013-.734q-.98 0-1.737.496q-.756.496-1.175 1.427l.92.386q.27-.63.787-1.005q.516-.374 1.166-.374q.821 0 1.346.474q.524.474.524 1.24q0 .461-.228.87t-.784.903q-.748.706-1.06 1.304t-.313 1.396");
}

</style>
