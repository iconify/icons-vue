<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="et2l-vl4c"/><path class="uz-m_1s9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-therapy" /></template>
<style>
.et2l-vl4c {
  d: path("M9 7.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-6.5 3.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM2.5 21v-2q0-.181.02-.361q.02-.179.06-.356q.04-.176.099-.347t.137-.334t.173-.317t.208-.296t.238-.271q.127-.128.268-.242m5.217 1.808Q9 18.638 9 19m8-8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM21.5 21v-2q0-.181-.02-.361q-.02-.179-.06-.356q-.04-.176-.099-.347t-.137-.334t-.173-.317t-.208-.296t-.238-.271q-.127-.128-.268-.242m-5.217 1.808Q15 18.638 15 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uz-m_1s9l {
  d: path("M6 21v-1.5a6 6 0 0 1 12 0V21");
}

</style>
