<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uf2-w4b_j"/><path class="px9j8bbzq"/><path class="ervqa2btt"/><path class="e2v-dxsfy"/><path class="ny6ragbew"/><path class="zjs2ddmvh"/><path class="djarqdbcn"/><path class="gp-s9bk_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-graphql" /></template>
<style>
.djarqdbcn {
  fill: var(--svg-color--e10098, #e10098);
  d: path("m15.734 27.042l9.962-5.752l.519.898l-9.963 5.752z");
}

.e2v-dxsfy {
  fill: var(--svg-color--e10098, #e10098);
  d: path("M5.002 10.174L16.456 3.56l.594 1.028l-11.455 6.614z");
}

.ervqa2btt {
  fill: var(--svg-color--e10098, #e10098);
  d: path("m4.999 21.828l.593-1.028l11.455 6.614l-.594 1.028zM14.95 4.59l.594-1.027l11.455 6.614l-.594 1.028z");
}

.gp-s9bk_m {
  fill: var(--svg-color--e10098, #e10098);
  d: path("M28.12 23a2.5 2.5 0 1 1-.915-3.411A2.5 2.5 0 0 1 28.12 23M8.2 11.5a2.5 2.5 0 1 1-.915-3.411A2.5 2.5 0 0 1 8.2 11.5M3.88 23a2.5 2.5 0 1 1 3.411.915A2.5 2.5 0 0 1 3.88 23M23.8 11.5a2.5 2.5 0 1 1 3.411.915A2.5 2.5 0 0 1 23.8 11.5M16 30a2.5 2.5 0 1 1 2.5-2.5A2.493 2.493 0 0 1 16 30m0-23.009a2.5 2.5 0 1 1 2.5-2.5a2.493 2.493 0 0 1-2.5 2.5");
}

.ny6ragbew {
  fill: var(--svg-color--e10098, #e10098);
  d: path("m14.743 3.508l1.028-.594l11.45 19.833l-1.027.593zM5.454 9.386h1.187v13.228H5.454z");
}

.px9j8bbzq {
  fill: var(--svg-color--e10098, #e10098);
  d: path("M4.545 21.162h22.902v1.187H4.545z");
}

.uf2-w4b_j {
  fill: var(--svg-color--e10098, #e10098);
  d: path("M4.781 22.746L16.232 2.914l1.028.593L5.81 23.34z");
}

.zjs2ddmvh {
  fill: var(--svg-color--e10098, #e10098);
  d: path("M25.36 9.386h1.187v13.228H25.36z");
}

</style>
