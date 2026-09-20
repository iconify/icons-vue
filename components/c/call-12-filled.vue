<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dc0ag6bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-12-filled" /></template>
<style>
.dc0ag6bdx {
  fill: currentColor;
  d: path("m5.966 4.49l-.827.742a5 5 0 0 0 .455 1.073a4.7 4.7 0 0 0 .722.922l1.071-.33c.6-.185 1.255.005 1.654.48l.61.726a1.47 1.47 0 0 1-.137 2.042c-.995.908-2.527 1.215-3.674.314a10.4 10.4 0 0 1-2.516-2.87A10 10 0 0 1 2.03 4.013c-.22-1.422.821-2.56 2.119-2.948c.774-.232 1.6.166 1.884.908l.335.875c.22.576.062 1.225-.402 1.641");
}

</style>
