<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="n1mjunbsu"><path class="whvzzy25r"/><path class="bjxrscbjk"/></g><g class="hkmbfwrqi"><path class="oc-kvzb8m"/><path class="t_8dcd2pf"/></g><path class="u0irm6bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-norway" /></template>
<style>
.bjxrscbjk {
  d: path("M20 4.5c-1 .4-2 1-3 1.5v52q1.5.9 3 1.5zm8-2.2v59.5l3 .3V2q-1.5 0-3 .3");
}

.hkmbfwrqi {
  fill: var(--svg-color--428bc1, #428bc1);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.oc-kvzb8m {
  d: path("M2 32c0 1.4.1 2.7.3 4h59.5c.2-1.3.3-2.6.3-4s-.1-2.7-.3-4H2.3c-.2 1.3-.3 2.6-.3 4");
}

.t_8dcd2pf {
  d: path("M20 59.5c2.5 1.1 5.2 1.9 8 2.2V2.3c-2.8.4-5.5 1.1-8 2.2z");
}

.u0irm6bsh {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M17 25V6C10 10.1 4.8 16.9 2.8 25zm0 14v19C10 53.9 4.8 47.1 2.8 39zM32 2h-1v23h30.2C58 11.8 46.2 2 32 2m-1 37v23h1c14.2 0 26-9.8 29.2-23z");
}

.whvzzy25r {
  d: path("M61.7 28c-.1-1-.3-2-.5-3H2.8c-.2 1-.4 2-.5 3zM2.3 36c.1 1 .3 2 .5 3h58.3c.2-1 .4-2 .5-3z");
}

</style>
