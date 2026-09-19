<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ik8-3_bxu"/><path class="s_5sk2igu"/><path class="oz55tab-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-maldives" /></template>
<style>
.ik8-3_bxu {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

.oz55tab-f {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  fill-rule: evenodd;
  d: path("M37.654 40.738a10.03 10.03 0 0 1-10.412-3.753c-2.632-3.494-2.666-8.406-.111-11.907a10.06 10.06 0 0 1 10.535-3.905c-2.711.138-4.996 1.12-6.832 3.059s-2.73 4.26-2.689 6.923c.076 5.078 4.156 9.39 9.509 9.583");
}

.s_5sk2igu {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M9 18h47v26H9z");
}

</style>
