<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><g class="n1mjunbsu"><path class="vpo1jjr7u"/><path class="myg18-brw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:japanese-congratulations-button" /></template>
<style>
.myg18-brw {
  d: path("M47.3 39.2c-.1 4.7-.3 5.4-.9 5.4h-1.2c-.6 0-.6-.1-.6-1.4V31.3h4.1V15H31.1v16.3h3c-.4 6.8-1.4 11.1-6.5 13.8c1 .9 2.2 2.7 2.8 3.9c6.3-3.4 7.7-9.1 8.2-17.7h1.8v11.9c0 4.1.8 5.4 4.1 5.4H47c2.7 0 3.7-1.6 4-7.7c-1.1-.3-2.9-1-3.7-1.7m-3.2-12.5h-8.5v-7.1h8.5z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.vpo1jjr7u {
  d: path("M27.4 39.2c-.7-1-1.9-2.5-3.2-3.9v14.2h-4.8V37.2c-1.4 1.2-2.7 2.3-4.1 3.2c-.4-1.3-1.5-3.8-2.2-4.6c3.8-2.1 7.5-5.8 9.8-9.9h-8.2v-4.6h4.8v-6.8h4.9v6.8h1.3l.9-.2l2.7 1.7c-1 2.7-2.3 5.2-3.9 7.6c1.8 1.4 4.5 3.9 5.3 4.7z");
}

</style>
