<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcpiw-96j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-kneeler-stool" /></template>
<style>
.bcpiw-96j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 12.25h-5.5V6.5q0-2.75-2.75-2.75T3.75 6.5v5.847q-.668.182-1.195.708q-.805.806-.805 1.945q0 2.47 2.219 2.722l-1.181 3.541q-.023.07-.032.143t-.004.147t.025.145t.052.137t.079.125q.045.058.101.107q.055.048.12.085q.064.036.134.06q.141.047.29.036q.149-.01.282-.077q.134-.067.232-.18q.097-.112.145-.254l1.329-3.987h12.918l1.329 3.987q.024.07.06.134q.037.065.085.12q.049.056.107.101q.059.046.125.079t.137.052q.071.02.145.025t.147-.004t.143-.032q.07-.024.134-.06q.065-.037.12-.085q.056-.049.101-.107q.046-.059.079-.125t.052-.137q.02-.071.025-.145t-.004-.147t-.032-.143l-1.181-3.541Q22.25 17.47 22.25 15q0-2.345-2-2.69V6.5q0-2.75-2.75-2.75T14.75 6.5zM5.25 6.5v5.75h2.5V6.5q0-1.25-1.25-1.25T5.25 6.5m11 5.75V6.5q0-1.25 1.25-1.25t1.25 1.25v5.75z");
}

</style>
