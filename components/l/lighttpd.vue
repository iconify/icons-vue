<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":211};
const content = `<path class="tv8m0_23h"/><path class="n_31khmsp"/><path class="dgwiacbex"/><path class="rhvutmqvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lighttpd" /></template>
<style>
.dgwiacbex {
  fill: var(--svg-color--d9e2e9, #d9e2e9);
  d: path("M31.347 152.679L256 0L0 123.839z");
}

.n_31khmsp {
  fill: var(--svg-color--8194a6, #8194a6);
  d: path("m46.081 194.998l5.015-28.526l1.176-.216L251.732 4.664L256 0l-7.561 4.193L31.524 151.445l-.177 1.234z");
}

.rhvutmqvi {
  fill: var(--svg-color--d7e0e5, #d7e0e5);
  d: path("m117.239 210.672l-66.143-44.2L256 0z");
}

.tv8m0_23h {
  fill: var(--svg-color--316682, #316682);
  d: path("m46.081 194.998l19.847-18.585l-.138-.87l-15.164-10.227l-4.643 27.742z");
}

</style>
