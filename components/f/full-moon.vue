<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="zef_6xa6v"/><g class="dt4yhf73z"><circle class="qkqe84bny"/><circle class="bdxd6db2u"/><circle class="r5fl0lb3y"/><circle class="bkx_pysua"/><circle class="l-elexbss"/><circle class="ho4lh1bfe"/><circle class="of3reof2o"/><circle class="g5q-qcc2j"/><circle class="ynx9hebhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:full-moon" /></template>
<style>
.bdxd6db2u {
  cx: 20px;
  cy: 17px;
  r: 3px;
}

.bkx_pysua {
  cx: 22px;
  cy: 5px;
  r: 2px;
}

.dt4yhf73z {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.g5q-qcc2j {
  cx: 32px;
  cy: 19px;
  r: 2px;
}

.ho4lh1bfe {
  cx: 30px;
  cy: 9px;
  r: 1px;
}

.l-elexbss {
  cx: 3px;
  cy: 18px;
  r: 1px;
}

.of3reof2o {
  cx: 15px;
  cy: 31px;
  r: 1px;
}

.qkqe84bny {
  cx: 10.5px;
  cy: 8.5px;
  r: 3.5px;
}

.r5fl0lb3y {
  cx: 24.5px;
  cy: 28.5px;
  r: 3.5px;
}

.ynx9hebhd {
  cx: 10px;
  cy: 23px;
  r: 2px;
}

.zef_6xa6v {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffd983, #ffd983);
}

</style>
