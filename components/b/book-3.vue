<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m542yft4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-3" /></template>
<style>
.m542yft4w {
  fill: currentColor;
  d: path("M7.616 21q-1.091 0-1.853-.763T5 18.386V6q0-1.239.868-2.12T8 3h11v13.77q-.688 0-1.152.475t-.463 1.14q0 .688.463 1.151T19 20v1zm1.436-8.23h.821l.587-1.584h3.056l.586 1.583h.802l-2.458-6.538h-.923zm1.68-2.34l1.257-3.36h.017l1.236 3.36zM7.617 20h9.363q-.285-.33-.44-.732q-.155-.4-.155-.884q0-.457.152-.87t.443-.745H7.616q-.689 0-1.152.476T6 18.385q0 .688.464 1.151T7.616 20");
}

</style>
