<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i2b6d14ke"/><path class="pk07sfbhl"/><path class="wu6yuabua"/><path class="l-bnxjs3o"/><path class="etlr6-bgy"/><g class="puvn5ac8d"><path class="a66t6acam"/><path class="tcqdlfbzn"/></g><path class="xlqp28b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-slovakia" /></template>
<style>
.a66t6acam {
  d: path("M23 23h2v14h-2z");
}

.etlr6-bgy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M16 21v11.9c0 5.6 4.3 8.6 8 10.1c3.7-1.5 8-4.5 8-10.1V21z");
}

.i2b6d14ke {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.l-bnxjs3o {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M33.9 19H14v13.8c0 9.2 9.6 12 10 12.2c.4-.2 10-3 10-12.2V19z");
}

.pk07sfbhl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.puvn5ac8d {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
}

.tcqdlfbzn {
  d: path("M19 29h10v2H19zm2-4h6v2h-6z");
}

.wu6yuabua {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.xlqp28b3e {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M24 35c-1.3 0-2.5.6-3.2 1.6q-.75-.6-1.8-.6c-.8 0-1.6.3-2.1.9c1.4 3.1 4.4 5 7.1 6.1c2.7-1.1 5.7-3 7.1-6.1c-.5-.6-1.3-.9-2.1-.9q-1.05 0-1.8.6c-.7-1-1.9-1.6-3.2-1.6");
}

</style>
