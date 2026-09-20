<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smy28bbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:album-sharp" /></template>
<style>
.smy28bbpd {
  fill: currentColor;
  d: path("M12 15.5q1.471 0 2.486-1.014Q15.5 13.47 15.5 12t-1.014-2.485T12 8.5T9.515 9.515T8.5 12t1.015 2.486T12 15.5m-.712-2.787Q11 12.425 11 12t.288-.712T12 11t.713.288T13 12t-.288.713T12 13t-.712-.288M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
