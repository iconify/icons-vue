<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkq9zsm0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-spark" /></template>
<style>
.jkq9zsm0k {
  fill: currentColor;
  d: path("M20 10V6.616q0-.231-.192-.424T19.385 6H16V5h3.385q.69 0 1.152.463T21 6.616V10zM3 10V6.616q0-.691.463-1.153T4.615 5H8v1H4.616q-.231 0-.424.192T4 6.616V10zm13 9v-1h3.385q.23 0 .423-.192t.192-.424V14h1v3.385q0 .69-.462 1.152T19.385 19zM4.615 19q-.69 0-1.153-.462T3 17.384V14h1v3.385q0 .23.192.423t.423.192H8v1zM12 16.096q.175 0 .2-.15q.362-1.39 1.359-2.387t2.387-1.359q.15-.05.15-.2q0-.175-.15-.2q-1.39-.362-2.387-1.359T12.2 8.054q-.03-.15-.2-.15q-.15 0-.2.15q-.362 1.39-1.359 2.387T8.054 11.8q-.15.025-.15.2q0 .15.15.2q1.39.362 2.387 1.359t1.359 2.387q.05.15.2.15");
}

</style>
