<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zhp0s6b5m"/><path class="g3qp0uwtq"/><path class="rjt2cib0t"/><path class="a553zobqy"/><path class="f3meywbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-flutter" /></template>
<style>
.a553zobqy {
  fill: var(--svg-color--095a9d, #095a9d);
  d: path("m15.435 26.675l4.262-4.237l7.292 7.375h-8.396z");
}

.f3meywbag {
  fill: var(--svg-color--0e5199, #0e5199);
  d: path("m15.435 26.675l3.971-1.321l-1.338-1.297z");
}

.g3qp0uwtq {
  fill: var(--svg-color--41d0fd, #41d0fd);
  d: path("m4.907 16.125l4.199 4.299L27.093 2.287h-8.349z");
}

.rjt2cib0t {
  fill: var(--svg-color--1fbcfd, #1fbcfd);
  d: path("m11.176 22.479l4.259 4.196l4.262-4.237l-4.314-4.122z");
}

.zhp0s6b5m {
  fill: var(--svg-color--40d0fd, #40d0fd);
  d: path("m15.383 18.316l3.361-3.274h8.349l-7.396 7.396z");
}

</style>
