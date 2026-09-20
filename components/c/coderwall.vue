<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ls9yahz8r"><circle class="k6l5_sb1p"/><circle class="c8vyhmbki"/><circle class="wb0kjqc7m"/><circle class="h8uhxbiwy"/><circle class="r9kq4e08n"/><circle class="inqp2ki_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:coderwall" /></template>
<style>
.c8vyhmbki {
  cx: 128px;
  cy: 28.823px;
  r: 28.051px;
}

.h8uhxbiwy {
  cx: 128px;
  cy: 128px;
  r: 28.051px;
}

.inqp2ki_b {
  cx: 227.177px;
  cy: 227.177px;
  r: 28.051px;
}

.k6l5_sb1p {
  cx: 28.823px;
  cy: 28.823px;
  r: 28.051px;
}

.ls9yahz8r {
  fill: var(--svg-color--3e8dcc, #3e8dcc);
}

.r9kq4e08n {
  cx: 227.177px;
  cy: 128px;
  r: 28.051px;
}

.wb0kjqc7m {
  cx: 227.177px;
  cy: 28.823px;
  r: 28.051px;
}

</style>
