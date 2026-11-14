<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_zs16b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:changing-bag" /></template>
<style>
.t_zs16b_m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.843 3.267q7.157-1.534 14.314 0q.098.021.186.066q.089.046.162.113t.128.151q.053.084.083.179q2.57 8.224 0 16.448q-.03.095-.083.179t-.128.151q-.073.067-.162.113q-.088.045-.186.066q-7.157 1.534-14.314 0q-.098-.021-.186-.066q-.089-.046-.162-.113t-.128-.151q-.053-.084-.083-.179q-2.57-8.224 0-16.448q.03-.095.083-.179t.128-.151q.073-.067.162-.113q.088-.045.186-.066M8.5 10.25q-2.75 0-2.75 2.75t2.75 2.75T11.25 13T8.5 10.25M12.75 13q0 2.75 2.75 2.75T18.25 13t-2.75-2.75T12.75 13");
}

</style>
