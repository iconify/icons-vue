<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="d4gjmmazr"/><path class="lol9h8w8o"/><path class="inwc3bcsc"/><path class="uowwz187x"/><path class="kdkbzs8zw"/><path class="ifo_2abup"/><path class="ssi48u96j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dbt-bouncer" /></template>
<style>
.d4gjmmazr {
  cx: 16px;
  cy: 16px;
  r: 15.36px;
  fill: var(--svg-color--130912, #130912);
}

.ifo_2abup {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M18.58 15.13a2.2 2.2 0 0 0 .93-1.44l.03-.21h-1.48a2.1 2.1 0 0 1-1.82-.95a.3.3 0 0 0-.48 0a2.1 2.1 0 0 1-1.82.95h-1.48l.03.21a2.2 2.2 0 0 0 .93 1.44l.3.21c.65.46 1.45 1.02 2.28 1.02s1.63-.56 2.28-1.02zm-4.31 1.42l-.06.45c.5.75 1.13 1.16 1.79 1.16s1.29-.41 1.79-1.16l-.06-.45a3.6 3.6 0 0 1-1.73.53a3.6 3.6 0 0 1-1.73-.53");
}

.inwc3bcsc {
  fill: var(--svg-color--ff694a, #ff694a);
  d: path("m11.7 10.62l-.03.07l.2 1.57a.56.56 0 0 0 .56.5h1.51a1.4 1.4 0 0 0 1.2-.6a1 1 0 0 1 1.72 0a1.4 1.4 0 0 0 1.2.6h1.51a.56.56 0 0 0 .56-.5l.2-1.57l-.02-.07l-.07-.03h-2.9a1 1 0 0 0-.57.17a1.4 1.4 0 0 1-.77.2a1.4 1.4 0 0 1-.77-.2a1 1 0 0 0-.58-.17h-2.89z");
}

.kdkbzs8zw {
  fill: var(--svg-color--ff694a, #ff694a);
  d: path("m18.5 26.1l-.54-.17a22 22 0 0 0-3.28-.8a19 19 0 0 1-1.93.97z");
}

.lol9h8w8o {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("m20.7 21.7l.2 1.03q.45.04.94.13a.36.36 0 1 1-.14.7a11 11 0 0 0-1.13-.14a8.3 8.3 0 0 0-4.88 1.15c.92.2 1.71.43 2.48.67a16 16 0 0 0 4.09.85a1.1 1.1 0 0 0 .87-.33a1.6 1.6 0 0 0 .44-1.2a15 15 0 0 0-.41-3.05z");
}

.ssi48u96j {
  fill: var(--svg-color--ff694a, #ff694a);
  d: path("M20.06 20.34a.36.36 0 0 1 .42.28l.07.37l2.6-.2a2 2 0 0 0 .06-.46c0-1.73-3.34-2.61-4.88-2.86c-.63.91-1.45 1.42-2.33 1.42s-1.7-.51-2.33-1.42c-1.55.25-4.88 1.13-4.88 2.86a2 2 0 0 0 .06.46l1.33.1l1.26.1l.08-.37a.36.36 0 0 1 .7.14l-.13.67v.01l-.2.98c1.54-.17 3.93-.25 5.74.56a8 8 0 0 1 2.52-.3l-.24-1.24l-.14-.68a.36.36 0 0 1 .29-.42");
}

.uowwz187x {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M11.48 23.2c-.67.1-1.1.19-1.11.2h-.08a.36.36 0 0 1-.08-.71c.01 0 .36-.09.92-.17l.17-.82l-2.46-.19a15 15 0 0 0-.41 3.05a1.6 1.6 0 0 0 .44 1.2a1.2 1.2 0 0 0 .87.33c1.96-.12 3.35-.9 4.7-1.65l.05-.03a20 20 0 0 1 2.06-1.05c-1.75-.5-3.85-.33-5.07-.16m3.17-13.33a1.7 1.7 0 0 1 .99.3a1 1 0 0 0 .36.06a1 1 0 0 0 .37-.07a1.7 1.7 0 0 1 .98-.29h2.62a3.97 3.97 0 0 0-7.94 0z");
}

</style>
