<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oajcm1b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:find-in-page-outline" /></template>
<style>
.oajcm1b2z {
  fill: currentColor;
  d: path("m15.442 20l1 1H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h7.923L19 8.346v11.039q0 .23-.126.46t-.328.409l-4.815-4.804q-.425.294-.84.422Q12.477 16 12 16q-1.237 0-2.119-.881T9 13t.877-2.119T12 10t2.123.881T15 13q0 .517-.137.93t-.413.8l3.55 3.6V8.7L14.05 4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192zm-2.03-5.587Q14 13.825 14 13t-.587-1.412T12 11t-1.412.588T10 13t.588 1.413T12 15t1.413-.587M12 12.5");
}

</style>
