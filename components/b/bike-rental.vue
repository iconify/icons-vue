<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1tml96mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-rental" /></template>
<style>
.t1tml96mu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 16.5q0-1.685-1.14-2.897L10 11.75l3.9 5.2q.076.101.18.171t.226.104q.208 1.3 1.189 2.28Q16.74 20.75 18.5 20.75t3.005-1.245T22.75 16.5t-1.245-3.005T18.5 12.25q-.479 0-.92.092l-.888-2.13q-.042-.103-.113-.189q-.071-.085-.163-.147t-.199-.094Q16.111 9.75 16 9.75h-6l-.029.001q-.083.003-.164.024t-.155.061t-.138.093t-.114.121l-1.982 2.643q-.867-.443-1.918-.443q-1.76 0-3.005 1.245T1.25 16.5t1.245 3.005T5.5 20.75t3.005-1.245T9.75 16.5m1.75-5.25h4l.696 1.669q-.369.244-.701.576q-.749.749-1.048 1.685z");
}

</style>
