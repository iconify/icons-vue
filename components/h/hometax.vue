<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shv07rbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hometax" /></template>
<style>
.shv07rbew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.742 30.34l9.604-8.64c.39-.35.799-.823 1.573-.823c.775 0 1.363.422 1.816.822l9.965 8.804h13.805c1.167 0 1.23-1.113.806-1.484L31.86 18.09c-.49-.43-1.21-.594-1.86-.594H18.259c-.505 0-.995.307-1.368.645L3.45 30.504h9.94");
}

</style>
