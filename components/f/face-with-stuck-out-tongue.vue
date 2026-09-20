<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="shvimactj"/><ellipse class="c7j88jbdk"/><path class="ouvf6xbxa"/><path class="sq_x0tbzl"/><path class="jy5siybcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-stuck-out-tongue" /></template>
<style>
.c7j88jbdk {
  cx: 24.5px;
  cy: 14.5px;
  fill: var(--svg-color--66471b, #66471b);
  rx: 2.5px;
  ry: 3.5px;
}

.jy5siybcm {
  fill: var(--svg-color--dd2f45, #dd2f45);
  d: path("M18 31.843a.545.545 0 0 0 .545-.545v-7.694l-1.091-.005v7.699a.546.546 0 0 0 .546.545");
}

.ouvf6xbxa {
  fill: var(--svg-color--66471b, #66471b);
  d: path("M7 21.262c0 3.964 4.596 9 11 9s11-5 11-9c0 0-10.333 2.756-22 0");
}

.shvimactj {
  cx: 11.5px;
  cy: 14.5px;
  fill: var(--svg-color--66471b, #66471b);
  rx: 2.5px;
  ry: 3.5px;
}

.sq_x0tbzl {
  fill: var(--svg-color--e8596e, #e8596e);
  d: path("m18.545 23.604l-1.091-.005c-3.216-.074-5.454-.596-5.454-.596v6.961c0 3 2 6 6 6s6-3 6-6v-6.92a29 29 0 0 1-5.455.56");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

</style>
