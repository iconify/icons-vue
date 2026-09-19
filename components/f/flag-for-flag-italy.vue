<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zzyf9-41q"/><path class="y7vz5ac5z"/><path class="t_rlincix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-italy" /></template>
<style>
.t_rlincix {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H42v44h12c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

.y7vz5ac5z {
  fill: var(--svg-color--29b473, #29b473);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.zzyf9-41q {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M22 10h20v44H22z");
}

</style>
