<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1h-d6crc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:devices-wearables-sharp" /></template>
<style>
.k1h-d6crc {
  fill: currentColor;
  d: path("M6 22V2h12.077v7.577h-4.262l-.492 3.271q-.813.829-1.26 1.886q-.448 1.058-.448 2.247t.454 2.281t1.273 1.928l.127.81zm6.588-15.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M15.885 22l-.325-2.108q-.727-.496-1.144-1.266T14 16.981t.416-1.646t1.143-1.266l.326-2.108h3.23l.326 2.108q.726.496 1.143 1.266q.416.77.416 1.646t-.416 1.645t-1.144 1.266L19.116 22zm3.39-3.244Q20 18.03 20 16.98t-.725-1.775t-1.775-.725t-1.775.725T15 16.98t.725 1.775t1.775.725t1.775-.725");
}

</style>
