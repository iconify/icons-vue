<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4_h_8imi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-wearables-outline-sharp" /></template>
<style>
.l4_h_8imi {
  fill: currentColor;
  d: path("M7 21V3zm5.588-14.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M13.469 22H6V2h12.077v7.577h-1V3H7v18h6.164q.04.052.086.098l.092.093zm2.416 0l-.325-2.108q-.727-.496-1.144-1.266T14 16.981t.416-1.646t1.143-1.266l.326-2.108h3.23l.326 2.108q.726.496 1.143 1.266q.416.77.416 1.646t-.416 1.645t-1.144 1.266L19.116 22zm3.39-3.244Q20 18.03 20 16.98t-.725-1.775t-1.775-.725t-1.775.725T15 16.98t.725 1.775t1.775.725t1.775-.725");
}

</style>
