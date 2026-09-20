<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h392yj-tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:book-4-rounded" /></template>
<style>
.h392yj-tc {
  fill: currentColor;
  d: path("M8.241 16.472q.143-.144.143-.357V4.5q0-.213-.143-.356Q8.097 4 7.884 4t-.356.144t-.143.356v11.616q0 .212.144.356t.356.143t.356-.143M6.231 21q-.93 0-1.58-.65Q4 19.698 4 18.77V5.23q0-.929.65-1.58Q5.302 3 6.23 3H15q.666 0 1.14.475q.476.474.476 1.14V16q0 .666-.475 1.14q-.475.476-1.141.476H6.23q-.501 0-.865.341Q5 18.3 5 18.804t.365.85t.866.346h12.154q.269 0 .442-.173t.173-.442V5.5q0-.213.144-.356T19.501 5t.356.144T20 5.5v13.885q0 .666-.475 1.14t-1.14.475z");
}

</style>
