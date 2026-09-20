<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="wo5qd-vuy"/><path class="ilhgobc6n"/><path class="wm-w77boy"/><path class="eviauhp2r"/><path class="w3sy7acig"/><path class="b6n_5bc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:barber-pole" /></template>
<style>
.b6n_5bc9e {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M27 11a2 2 0 0 1-2 2H11a2 2 0 0 1 0-4h14a2 2 0 0 1 2 2m0 23a2 2 0 0 1-2 2H11a2 2 0 0 1 0-4h14a2 2 0 0 1 2 2");
}

.eviauhp2r {
  fill: var(--svg-color--55acee, #55acee);
  d: path("m11 19.585l14 6.83v-4.45l-14-6.831z");
}

.ilhgobc6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 12h14v21H11z");
}

.w3sy7acig {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M13.697 12L25 17.514V12z");
}

.wm-w77boy {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M11 28.487L20.251 33H25v-2.134l-14-6.83z");
}

.wo5qd-vuy {
  cx: 18px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

</style>
