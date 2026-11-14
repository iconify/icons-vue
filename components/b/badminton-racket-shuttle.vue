<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3rtebxif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:badminton-racket-shuttle" /></template>
<style>
.o3rtebxif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.575 3.833Q7.25 5.572 7.25 8q0 1.712.659 3.082q-.106.054-.189.138l-5.25 5.25q-.053.052-.094.113t-.069.13t-.043.141T2.25 17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T3 17.75t.287-.057t.243-.163l5.186-5.185Q10.073 14 12 14q2.028 0 3.425-1.833Q16.75 10.428 16.75 8t-1.325-4.167Q14.028 2 12 2T8.575 3.833m11.074 12.34l-1.037-1.97q-.53-1.006-1.654-1.177q-1.124-.17-1.928.634l-1.37 1.37q-.804.804-.634 1.928t1.177 1.654l1.97 1.037q.562.296 1.081.306q.101 2.295 2.496 2.295q1.036 0 1.768-.732t.732-1.768t-.732-1.768q-.659-.658-1.563-.725q-.009-.52-.306-1.084");
}

</style>
