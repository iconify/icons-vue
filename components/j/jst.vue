<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ucmh0kbjc"><path class="b2ktlbc5y"/><path class="hv2-wccqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:jst" /></template>
<style>
.b2ktlbc5y {
  d: path("M14.119 5.118a2.118 2.118 0 1 1-4.235 0a2.118 2.118 0 0 1 4.235 0m0 13.764a2.118 2.118 0 1 1-4.235 0a2.118 2.118 0 0 1 4.235 0m-10.06-5.824h15.884v2.648H4.06z");
}

.hv2-wccqz {
  d: path("M3.529 3.528c.201 4.42 3.917 7.942 8.47 7.942c4.555 0 8.27-3.522 8.472-7.942h-2.665c-.27 2.912-2.767 5.192-5.805 5.192c-3.039 0-5.534-2.28-5.805-5.192z");
}

.ucmh0kbjc {
  fill: var(--svg-color--b41514, #b41514);
}

</style>
