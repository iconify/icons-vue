<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="u-85q7evm"/><circle class="ao1eh_btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-palau" /></template>
<style>
.ao1eh_btz {
  cx: 24px;
  cy: 32px;
  r: 16px;
  fill: var(--svg-color--ffe62e, #ffe62e);
}

.u-85q7evm {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--42ade2, #42ade2);
}

</style>
