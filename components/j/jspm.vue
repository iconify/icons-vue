<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":298};
const content = `<path class="fdmycubbr"/><path class="f6406n61f"/><path class="lqyhvo_xx"/><path class="pq6-2_ooi"/><path class="m2h714baz"/><path class="ausjttkmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:jspm" /></template>
<style>
.ausjttkmq {
  fill: var(--svg-color--a5a5a4, #a5a5a4);
  d: path("m101.559 164.147l-76.857-44.342v89.393l76.857 44.358zM0 74.867l126.985 73.78l-.056 149.264L0 224.77z");
}

.f6406n61f {
  fill: var(--svg-color--e0cc41, #e0cc41);
  d: path("m104.25 258.24l-82.239-47.465v-95.653l82.239 47.447z");
}

.fdmycubbr {
  fill: var(--svg-color--feea5f, #feea5f);
  d: path("m210.741 74.865l-82.858 47.877L44.959 74.88l82.915-47.886z");
}

.lqyhvo_xx {
  fill: var(--svg-color--efdb50, #efdb50);
  d: path("m150.051 161.649l84.853-48.988v99.186l-84.853 48.971z");
}

.m2h714baz {
  fill: var(--svg-color--b3b3b3, #b3b3b3);
  d: path("m154.24 253.505l76.476-44.137v-89.394l-76.477 44.152zm-27.311-104.859l129.059-73.778v149.337l-129.06 73.707l-6.546-73.707z");
}

.pq6-2_ooi {
  fill: var(--svg-color--c3c2c2, #c3c2c2);
  d: path("m50.435 74.879l77.446 44.7l77.384-44.714l-77.393-44.708zM127.658 0l128.33 74.699l-61.239 48.043l-67.764 25.904l-63.565-20.762L0 74.69z");
}

</style>
