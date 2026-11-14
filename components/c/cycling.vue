<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ffjvd1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cycling" /></template>
<style>
.j1ffjvd1h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 4q0-1.375.688-2.062q.687-.688 2.062-.688q2.75 0 2.75 2.75T14 6.75T11.25 4m1.256 2.936l-4 3.5q-.092.08-.154.186l-1.385 2.375q-.682-.247-1.467-.247q-1.76 0-3.005 1.245T1.25 17t1.245 3.005T5.5 21.25t3.005-1.245T9.75 17t-1.245-3.005q-.122-.122-.248-.232l1.152-1.976l5.158.43l1.054 1.656q-.064.059-.126.122Q14.25 15.24 14.25 17t1.245 3.005T18.5 21.25t3.005-1.245T22.75 17t-1.245-3.005T18.5 12.75q-.874 0-1.62.307l-.928-1.458q.058-.044.106-.098q.049-.054.086-.117q.037-.062.062-.13q.024-.069.035-.14t.008-.145q-.003-.072-.019-.143q-.017-.071-.047-.137t-.073-.125l-2.5-3.5q-.021-.03-.046-.058q-.098-.112-.232-.178q-.133-.066-.282-.076t-.29.038q-.142.047-.254.146m1.854 3.758l-3.535-.294l2.046-1.79z");
}

</style>
