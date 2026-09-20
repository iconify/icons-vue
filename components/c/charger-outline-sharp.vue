<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2il8o8zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:charger-outline-sharp" /></template>
<style>
.t2il8o8zw {
  fill: currentColor;
  d: path("m11.8 19.23l3.039-8.518H12.3V4.654l-3.039 8.558H11.8zm.203 1.77q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709m5.66-3.337Q20 15.325 20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337");
}

</style>
