<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tv8-sbbzs"/><path class="agg9nrr2f"/><path clip-rule="evenodd" class="hsq9hbb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-frontcommerce-opened" /></template>
<style>
.agg9nrr2f {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("M23.814 29.366a6.985 6.985 0 1 0 0-13.97a6.985 6.985 0 0 0 0 13.97");
}

.hsq9hbb5i {
  fill: var(--svg-color--ac304f, #ac304f);
  fill-rule: evenodd;
  d: path("M30.1 22.381a6.287 6.287 0 1 1-12.573 0a6.287 6.287 0 0 1 12.574 0m-4.193-1.226l2.098-1.22l-4.19-2.444l-4.192 2.443v4.886l2.1 1.224l-.002-2.449l2.093 1.22v2.456l4.191-2.451l-2.098-1.229l-2.093 1.224v-2.438l-2.093-1.222l2.093-1.22z");
}

.tv8-sbbzs {
  fill: var(--svg-color--d42551, #d42551);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21zm-7.2 2.1h7.1v2.1h-8.1zm5.5 6.1H6.6v-1.9h20.8v7.626z");
}

</style>
