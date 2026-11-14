<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_i8qfwlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carbon-dioxide" /></template>
<style>
.n_i8qfwlo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 8Q9.354 8 8.458 9.75H6.345q-.672-.5-1.845-.5q-2.75 0-2.75 2.75t2.75 2.75q1.173 0 1.845-.5h2.113Q9.354 16 12 16t3.542-1.75h2.113q.672.5 1.845.5q2.75 0 2.75-2.75T19.5 9.25q-1.173 0-1.845.5h-2.34q-.211-.303-.487-.578Q13.657 8 12 8m3.936 3.25h.874q-.06.345-.06.75t.06.75h-.849Q16 12.394 16 12q0-.388-.064-.75m-8.746 0h.849Q8 11.606 8 12t.039.75H7.19q.06-.345.06-.75t-.06-.75");
}

</style>
