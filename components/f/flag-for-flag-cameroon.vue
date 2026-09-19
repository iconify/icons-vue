<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t765msbpf"/><path class="cb6h9mbxr"/><path class="qfixqzbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-cameroon" /></template>
<style>
.cb6h9mbxr {
  fill: var(--svg-color--007a5e, #007a5e);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.qfixqzbej {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M54 10H42v44h12c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11M40.462 28.689l-6.202.011l-1.92-6.274l-1.914 6.274l-6.206-.011l5.03 3.822l-1.952 6.232l5.05-3.871l5.05 3.871l-1.958-6.232z");
}

.t765msbpf {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M22 10h20v44H22z");
}

</style>
