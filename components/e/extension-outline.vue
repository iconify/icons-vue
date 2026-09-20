<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6mtu66me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-outline" /></template>
<style>
.j6mtu66me {
  fill: currentColor;
  d: path("M5.442 19.116h12.231q.193 0 .318-.135t.125-.327v-4.216l.72-.242q.516-.142.84-.627T20 12.442q0-.655-.324-1.133t-.84-.64l-.72-.236V6.23q0-.212-.126-.337t-.317-.125h-4.127l-.115-.854q-.114-.742-.632-1.27t-1.241-.53q-.73 0-1.248.53t-.631 1.27l-.116.854h-4.14q-.173 0-.298.125T5 6.231V8.65q1.189.333 2.008 1.402t.819 2.39q0 1.366-.81 2.435q-.81 1.07-2.017 1.363v2.414q0 .192.125.327q.125.134.317.134m0 1q-.6 0-1.02-.43Q4 19.254 4 18.654V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416V6.23q0-.614.415-1.038q.414-.424 1.008-.424h3.262q.156-1.121.957-1.887q.802-.766 1.916-.766q1.108 0 1.91.766t.963 1.887h3.242q.594 0 1.018.424t.425 1.038v3.485q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.053v3.485q0 .6-.425 1.03q-.424.432-1.018.432zm7.058-7.673");
}

</style>
