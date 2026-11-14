<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m08uztqml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bulk-bag" /></template>
<style>
.m08uztqml {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.719 5.75h4.562q.259-3 2.719-3q2.684 0 2.748 3.572Q21.25 9.427 21.25 13.5q0 4.177-1.579 7.335q-.047.094-.117.171t-.16.132q-.089.055-.189.083q-.101.029-.205.029H5q-.104 0-.205-.029q-.1-.028-.189-.083t-.16-.132t-.117-.171Q2.75 17.677 2.75 13.5q0-4.073 1.502-7.178Q4.316 2.75 7 2.75q2.46 0 2.719 3m-1.511 0Q8.021 4.25 7 4.25t-1.208 1.5zM17 4.25q-1.021 0-1.208 1.5h2.416q-.187-1.5-1.208-1.5");
}

</style>
