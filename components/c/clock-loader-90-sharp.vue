<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_t3_37qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clock-loader-90-sharp" /></template>
<style>
.k_t3_37qp {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708M6.344 6.34L12 12V4q-1.6 0-3.065.61q-1.466.61-2.59 1.731");
}

</style>
