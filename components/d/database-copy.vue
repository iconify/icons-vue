<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njgksl7qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-copy" /></template>
<style>
.njgksl7qz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.74 2.496q3.282-1.211 7.426-.533q4.574.749 4.584 3.034V15q.015 1.688-2.763 2.612q-.071.023-.144.032t-.147.004t-.145-.025q-.071-.019-.137-.052q-.066-.034-.124-.079q-.059-.045-.107-.101t-.085-.12q-.036-.064-.06-.134q-.023-.071-.032-.144t-.004-.147t.025-.145q.019-.071.052-.137q.034-.066.079-.124q.045-.059.101-.107t.12-.085t.134-.06q1.742-.579 1.737-1.188V5.003q-.004-1.016-3.326-1.559q-3.754-.614-6.664.46q-.07.025-.143.037t-.146.008q-.074-.002-.146-.02q-.072-.017-.139-.048t-.127-.074q-.06-.044-.11-.098t-.088-.117t-.065-.132q-.051-.14-.045-.289t.068-.285t.172-.237t.249-.153M2.25 9q0-3.25 7.25-3.25T16.75 9v9.5q0 3.25-7.25 3.25T2.25 18.5zm1.5 2.284V18.5q0 1.75 5.75 1.75t5.75-1.75v-7.216q-1.798.966-5.75.966t-5.75-.966");
}

</style>
