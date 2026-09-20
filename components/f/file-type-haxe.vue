<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n57oxvemg"/><path class="jpvzngbsi"/><path class="r4-99dz-p"/><path class="z5ef8i5mb"/><path class="nx6cbzbgc"/><path class="co6b_pwjx"/><path class="jn8q1dbqk"/><path class="z66024bqo"/><path class="n9u55o57t"/><path class="z1_547b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-haxe" /></template>
<style>
.co6b_pwjx {
  fill: var(--svg-color--fbc707, #fbc707);
  d: path("M16 5.5L2 2h7zm0 0L30 2h-7z");
}

.jn8q1dbqk {
  fill: var(--svg-color--f68712, #f68712);
  d: path("M16 26.5L30 30h-7z");
}

.jpvzngbsi {
  fill: var(--svg-color--fab20b, #fab20b);
  d: path("m2 2l14 3.5L5.5 16z");
}

.n57oxvemg {
  fill: var(--svg-color--f68712, #f68712);
  d: path("M16 5.5L5.5 16L16 26.5L26.5 16z");
}

.n9u55o57t {
  fill: var(--svg-color--fff200, #fff200);
  d: path("M5.5 16L2 30v-7zm0 0L2 2v7z");
}

.nx6cbzbgc {
  fill: var(--svg-color--f89c0e, #f89c0e);
  d: path("m2 30l3.5-14L16 26.5z");
}

.r4-99dz-p {
  fill: var(--svg-color--f47216, #f47216);
  d: path("m30 2l-3.5 14L16 5.5z");
}

.z1_547b0q {
  fill: var(--svg-color--f1471d, #f1471d);
  d: path("M26.5 16L30 2v7zm0 0L30 30v-7z");
}

.z5ef8i5mb {
  fill: var(--svg-color--f25c19, #f25c19);
  d: path("m30 30l-14-3.5L26.5 16z");
}

.z66024bqo {
  fill: var(--svg-color--f25c19, #f25c19);
  d: path("M16 26.5L2 30h7z");
}

</style>
