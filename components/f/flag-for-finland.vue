<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n6j7f3fqk"/><path class="eoj3fnesg"/><path class="s87cl7bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-finland" /></template>
<style>
.eoj3fnesg {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M18 10h11v44H18z");
}

.n6j7f3fqk {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

.s87cl7bbl {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M0 27h64v10H0z");
}

</style>
